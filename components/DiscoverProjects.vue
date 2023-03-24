<script setup lang="ts">
  defineProps({
    name: {
      type: String,
      default: 'DiscoverProjects',
    },
  })
</script>

<template>
  <section class="bg-primary-500 py-24 text-white">
    <div class="container mx-auto px-4 relative">
      <div class="mb-8 text-center">
        <h2 class="font-bold mb-2 text-5xl">Discover Projects</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam vitae
          congue tortor.
        </p>
      </div>
      <div class="-mx-4 flex flex-wrap justify-center">
        <div class="px-4 w-full lg:w-10/12">
          <div class="-mx-1 flex flex-wrap">
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1513633200258-fcd8728b598d?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDIyMXx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0ODMxOTA0&amp;ixlib=rb-1.2.1q=85&amp;fm=jpg&amp;crop=faces&amp;cs=srgb&amp;w=300&amp;h=300&amp;fit=crop"
                  class="group-hover:opacity-90 w-full"
                  width="300"
                  height="300"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 1</p>
                </div>
              </a>
            </div>
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1535077863442-d02c5a67da76?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDczOXx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0OTA1MjQ1&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=300&fit=crop"
                  width="300"
                  height="300"
                  class="group-hover:opacity-90 w-full"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 2</p>
                </div>
              </a>
            </div>
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1475813664016-f6a7ecaee6bf?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDY5NXx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0OTA1MjM3&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=300&fit=crop"
                  width="300"
                  height="300"
                  class="group-hover:opacity-90 w-full"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 3</p>
                </div>
              </a>
            </div>
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1535715145821-23c425db8a2c?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDU4M3x8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0OTA1MTky&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=300&fit=crop"
                  width="300"
                  height="300"
                  class="group-hover:opacity-90 w-full"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 4</p>
                </div>
              </a>
            </div>
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1519515449982-8b104b672029?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDl8fHR1cnRsZXxlbnwwfHx8fDE2MjQ5MTMzNTk&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=300&fit=crop"
                  width="300"
                  height="300"
                  class="group-hover:opacity-90 w-full"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 5</p>
                </div>
              </a>
            </div>
            <div class="p-1 text-primary-500 w-6/12 lg:w-4/12">
              <a
                href="#"
                class="block group hover:text-primary-600 relative text-primary-500"
                ><img
                  src="https://images.unsplash.com/photo-1559417050-039d66224d3d?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDE0Mnx8ZWxlcGhhbnR8ZW58MHx8fHwxNjI0OTEzMzM4&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=300&h=300&fit=crop"
                  width="300"
                  height="300"
                  class="group-hover:opacity-90 w-full"
                />
                <div
                  class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10"
                >
                  <p class="font-bold">Project 6</p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
