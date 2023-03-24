<script setup lang="ts">
  defineProps({
    name: {
      type: String,
      default: 'HeroSection',
    },
  })
</script>

<template>
  <section class="bg-primary-900 poster relative text-white">
    <div class="shadow">
      <div class="container mx-auto">
        <nav class="flex flex-wrap items-center p-4">
          <a class="hover:text-gray-200 mr-auto text-white text-xl" href="#"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              height="2em"
              width="2em"
              class="inline mr-2"
            >
              <path
                d="M512 256c0 141.4-114.6 256-256 256S0 397.4 0 256 114.6 0 256 0s256 114.6 256 256z"
                fill="currentColor"
                class="text-primary-500"
              ></path>
              <g fill="currentColor" class="text-gray-800">
                <path
                  d="M351.2 232c16.7 16.7 16.7 43.9 0 60.6l-61.7 61.7c-16.7 16.7-43.9 16.7-60.6 0l-.2-.2c-16.7-16.7-16.7-43.9 0-60.6l61.7-61.7c16.7-16.7 43.9-16.7 60.6 0l.2.2z"
                ></path>
                <path
                  d="M297.4 239.4c21.1 21.1 24.6 52 7.7 68.9-16.9 16.9-47.7 13.5-68.9-7.7-21.1-21.1-24.6-52-7.7-68.9 16.9-16.9 47.8-13.5 68.9 7.7zm-36.2-84.9c13.1 13.1 13.1 34.2 0 47.3-13.1 13.1-34.2 13.1-47.3 0-13.1-13.1-13.1-34.2 0-47.3 13.1-13.1 34.2-13.1 47.3 0zm-62.6 62.6c13.1 13.1 13.1 34.2 0 47.3-13.1 13.1-34.2 13.1-47.3 0-13.1-13.1-13.1-34.2 0-47.3 13.1-13.1 34.2-13.1 47.3 0zM194.1 303c10.9 10.9 10.9 28.7 0 39.6-10.9 10.9-28.7 10.9-39.6 0-10.9-10.9-10.9-28.7 0-39.6 10.9-10.9 28.6-10.9 39.6 0zm145.4-145.4c10.9 10.9 10.9 28.7 0 39.6-10.9 10.9-28.7 10.9-39.6 0-10.9-10.9-10.9-28.7 0-39.6 10.9-10.9 28.6-10.9 39.6 0z"
                ></path>
              </g></svg
            ><span class="font-sans relative text-2xl top-1"
              >The Spotted Kingfisher</span
            ></a
          >
          <button
            class="hover:bg-primary-600 hover:text-white px-3 py-2 rounded text-primary-600 lg:hidden"
            data-name="nav-toggler"
            data-pg-ia='{"l":[{"name":"NabMenuToggler","trg":"click","a":{"l":[{"t":"^nav|[data-name=nav-menu]","l":[{"t":"set","p":0,"d":0,"l":{"class.remove":"hidden"}}]},{"t":"#gt# span:nth-of-type(1)","l":[{"t":"tween","p":0,"d":0.2,"l":{"rotationZ":45,"yPercent":300}}]},{"t":"#gt# span:nth-of-type(2)","l":[{"t":"tween","p":0,"d":0.2,"l":{"autoAlpha":0}}]},{"t":"#gt# span:nth-of-type(3)","l":[{"t":"tween","p":0,"d":0.2,"l":{"rotationZ":-45,"yPercent":-300}}]}]},"pdef":"true","trev":"true"}]}'
            data-pg-ia-apply="$nav [data-name=nav-toggler]"
          >
            <span class="block border-b-2 border-current my-1 w-6"></span
            ><span class="block border-b-2 border-current my-1 w-6"></span
            ><span class="block border-b-2 border-current my-1 w-6"></span>
          </button>
          <div
            class="lg:flex lg:space-x-4 lg:space-y-0 lg:w-auto space-y-2 w-full hidden lg:items-center"
            data-name="nav-menu"
          >
            <div class="flex flex-col lg:flex-row">
              <a
                href="#"
                class="hover:text-primary-500 px-0 py-2 text-white lg:px-6"
                >Home</a
              ><a
                href="#"
                class="hover:text-primary-500 px-0 py-2 text-white lg:px-6"
                >About</a
              ><a
                href="#"
                class="hover:text-primary-500 px-0 py-2 text-white lg:px-6"
                >Discover</a
              ><a
                href="#"
                class="hover:text-primary-500 px-0 py-2 text-white lg:px-6"
                >Our Work</a
              ><a
                href="#"
                class="hover:text-primary-500 px-0 py-2 text-white lg:px-6"
                >Contact</a
              >
            </div>
            <a
              href="#"
              class="bg-white hover:bg-primary-500 inline-block px-12 py-4 rounded-full text-gray-900"
              >Donate</a
            >
          </div>
        </nav>
      </div>
    </div>
    <div class="container mx-auto px-4 py-36">
      <div class="-mx-4 flex flex-wrap">
        <div class="px-4 w-full lg:w-7/12 2xl:w-6/12">
          <h1 class="font-light mb-4 text-6xl sm:text-7xl xl:text-8xl">
            Help the World&rsquo;s Most
            <span class="font-bold">Iconic Species</span>
          </h1>
          <p class="mb-6 text-xl sm:pr-12">
            Conserve the world&apos;s most important forests to sustain
            nature&apos;s diversity, benefit our climate, and support human
            well-being.
          </p>
          <a
            href="#"
            class="bg-primary-500 hover:bg-primary-400 inline-block px-12 py-4 rounded-full text-gray-900"
            >Explore</a
          >
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
