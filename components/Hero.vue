<template lang="">
  <section class="px-2 bg-white md:px-0">
    <div class="container items-center max-w-6xl px-8 mx-auto xl:px-5">
      <div class="flex flex-wrap items-center sm:-mx-3">
        <div class="w-full md:w-1/2 md:px-3 order-2 lg:order-1">
          <div
            class="w-full pb-6 space-y-6 sm:max-w-md lg:max-w-lg md:space-y-4 lg:space-y-8 xl:space-y-9 sm:pr-5 lg:pr-0 md:pb-0"
          >
            <h1
              class="text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl md:text-4xl lg:text-5xl xl:text-6xl"
            >
              <span class="block xl:inline">World's First</span>
              <span class="block text-indigo-600 xl:inline"
                >Automated Cleaning Service.</span
              >
            </h1>
            <p
              class="mx-auto text-base text-gray-500 sm:max-w-md lg:text-xl md:max-w-3xl"
            >
              Browse through our catalog of roombas and have an automatic
              cleaning robot delivered to your house today.
            </p>
            <div class="relative flex flex-col sm:flex-row sm:space-x-4">
              <a
                href="#"
                class="flex items-center justify-center w-full px-6 py-3 mb-3 text-lg text-white bg-indigo-600 rounded-full sm:mb-0 hover:bg-indigo-700 sm:w-auto transform hover:scale-105 transition ease-out duration-300"
              >
                Get Yours Now
                <font-awesome-icon
                  icon="arrow-right"
                  size="sm"
                  class="ml-2"
                ></font-awesome-icon>
              </a>
              <a
                href="#"
                class="flex items-center justify-center px-6 py-3 text-gray-500 hover:text-gray-800 transform hover:scale-105 transition ease-out duration-300"
              >
                Learn More
              </a>
            </div>
          </div>
        </div>
        <div class="w-full md:w-1/2 order-1 lg:order-2">
          <img src="~/assets/img/cleaning-robot.svg" alt="cleaning-robot" />
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {}
</script>
