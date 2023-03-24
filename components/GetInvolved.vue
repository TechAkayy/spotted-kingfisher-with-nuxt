<script setup lang="ts">
  defineProps({
    name: {
      type: String,
      default: 'GetInvolved',
    },
  })
</script>

<template>
  <section class="py-24">
    <div class="container mx-auto px-4 relative">
      <div class="mb-8 text-center">
        <h2 class="font-bold mb-2 text-5xl text-gray-800">Get Involved</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam vitae
          congue tortor.
        </p>
      </div>
      <div class="flex flex-wrap -mx-4">
        <div class="px-4 w-full xl:w-7/12">
          <div class="flex flex-wrap -mx-4">
            <div class="p-4 w-full md:w-6/12">
              <div class="bg-black bg-opacity-90 h-full">
                <img
                  src="https://images.unsplash.com/photo-1505134222155-9a141dc0594d?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDIxMHx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0ODMxOTA0&amp;ixlib=rb-1.2.1q=85&amp;fm=jpg&amp;crop=faces&amp;cs=srgb&amp;w=300&amp;h=300&amp;fit=crop"
                  width="300"
                  height="300"
                  class="w-full"
                />
                <div class="border-primary-500 border-t-4 p-12">
                  <h3 class="font-bold font-serif mb-6 text-white text-xl">
                    Conservation of Red Pandas Project
                  </h3>
                  <a
                    href="#"
                    class="bg-white hover:bg-primary-500 inline-block px-6 py-2 rounded-full text-gray-900 text-sm"
                    >Learn More</a
                  >
                </div>
              </div>
            </div>
            <div class="p-4 w-full md:w-6/12">
              <div class="bg-black bg-opacity-90 h-full">
                <img
                  src="https://images.unsplash.com/reserve/iZkDQMqeQlqhoCIywoFv_6005485056_c8622e0824_o.jpg?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDE2NHx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0ODMxODk4&amp;ixlib=rb-1.2.1q=85&amp;fm=jpg&amp;crop=faces&amp;cs=srgb&amp;w=300&amp;h=300&amp;fit=crop"
                  width="300"
                  height="300"
                  class="w-full"
                />
                <div class="border-primary-500 border-t-4 p-12">
                  <h3 class="font-bold font-serif mb-6 text-white text-xl">
                    Wildlife Crime Technology Project
                  </h3>
                  <a
                    href="#"
                    class="bg-white hover:bg-primary-500 inline-block px-6 py-2 rounded-full text-gray-900 text-sm"
                    >Learn More</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="p-4 w-full xl:w-5/12">
          <div class="bg-black bg-opacity-90 h-full relative">
            <img
              src="https://images.unsplash.com/photo-1534995890293-84afcbee574f?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDczOHx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0OTA1MjQ1&ixlib=rb-1.2.1q=85&fm=jpg&crop=faces&cs=srgb&w=608&h=632&fit=crop"
              height="578"
              width="520"
              class="h-96 object-cover w-full sm:h-full"
            />
            <div
              class="absolute border-b-4 border-primary-500 bottom-0 inset-x-0 p-8 z-10 sm:p-12"
            >
              <div class="flex flex-wrap items-center space-y-4 sm:space-y-0">
                <div class="pr-2 w-full sm:flex-1">
                  <h3 class="font-bold font-serif text-2xl text-white">
                    Conserving Rhinos and Securing Water Resources
                  </h3>
                </div>
                <div class="w-full sm:w-auto">
                  <a
                    href="#"
                    class="bg-white hover:bg-primary-500 inline-block px-6 py-2 rounded-full text-gray-900 text-sm"
                    >Learn More</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
