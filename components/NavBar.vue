<script setup lang="ts">
  import { useRouter, useRoute } from 'vue-router'
  import { computed } from 'vue'

  // import { useScriptTag } from '@vueuse/core'
  // useScriptTag(
  //   '/pgia/lib/index1.js',
  //   // on script tag loaded.
  //   () => {
  //     // do something
  //   },
  // )
  // useScriptTag(
  //   'https://player.twitch.tv/js/embed/v1.js',
  //   // on script tag loaded.
  //   () => {
  //     // do something
  //   },
  // )

  //   const { scriptTag, load, unload } = useScriptTag(
  //     '/pgia/lib/index1.js',
  //     () => {
  //       // do something
  //     },
  //     { manual: true },
  //   )

  //   // manual controls
  // await load()
  // await unload()

  // const { site } = usePage()

  const routes = useRouter().getRoutes()

  const navLinksFromRouter = routes
    // Filter out routes starting with upper-case, for eg, NotFoundInDev
    .filter((route) => route.name[0] !== route.name[0].toUpperCase())
    .sort((a, b) => (a.meta.navOrder > b.meta.navOrder ? 1 : -1))
    .map((route) => {
      return {
        text: route.meta.title || route.name,
        link: route.path,
      }
    })

  const navlinks = computed(() => /*site.nav ||*/ navLinksFromRouter)

  const currentRoute = useRoute()
</script>
<template>
  <div>
    <header class="bg-gray-100 text-gray-200">
      <nav
        class="bg-gray-800 container flex flex-wrap items-center mx-auto px-4 py-8"
      >
        <NuxtLink
          class="flex font-medium hover:text-blue-800 items-center mr-auto text-2xl text-blue-600 uppercase"
          to="/"
          ><Icon name="noto-v1:beach-with-umbrella" width="48px"></Icon
          ><span class="capitalize ml-4 text-gray-100">Funtopia</span>
        </NuxtLink>
        <button
          class="hover:bg-gray-700 hover:text-white px-3 py-2 rounded text-gray-300 lg:hidden"
          data-name="nav-toggler"
          data-pg-ia='{"l":[{"name":"NabMenuToggler","trg":"click","a":{"l":[{"t":"^nav|[data-name=nav-menu]","l":[{"t":"set","p":0,"d":0,"l":{"class.remove":"hidden"}}]},{"t":"#gt# span:nth-of-type(1)","l":[{"t":"tween","p":0,"d":0.2,"l":{"rotationZ":45,"yPercent":300}}]},{"t":"#gt# span:nth-of-type(2)","l":[{"t":"tween","p":0,"d":0.2,"l":{"autoAlpha":0}}]},{"t":"#gt# span:nth-of-type(3)","l":[{"t":"tween","p":0,"d":0.2,"l":{"rotationZ":-45,"yPercent":-300}}]}]},"pdef":"true","trev":"true"}]}'
        >
          <span class="block border-b-2 border-current my-1 w-6"></span>
          <span class="block border-b-2 border-current my-1 w-6"></span>
          <span class="block border-b-2 border-current my-1 w-6"></span>
        </button>
        <div
          class="lg:flex lg:space-x-4 lg:space-y-0 lg:w-auto space-y-2 w-full hidden lg:items-center"
          data-name="nav-menu"
        >
          <div class="flex flex-col space-x-2 lg:flex-row">
            <NuxtLink
              v-for="(navlink, index) in navlinks"
              :key="index"
              class="capitalize font-light hover:bg-gray-700 hover:text-white px-0 py-2 rounded-lg text-gray-300 lg:px-4"
              :class="{
                'bg-gray-900 text-white': navlink.link === currentRoute.path,
              }"
              :to="navlink.link"
              >{{ navlink.text }}</NuxtLink
            >
          </div>
        </div>
      </nav>
    </header>
  </div>
</template>
<style scoped></style>
