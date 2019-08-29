<template>
    <div id="app">
      <div class="bg-gray-100 flex">
      <div
        class="px-8 py-12 mx-w-md mx-auto sm:max-w-xl lg:max-w-full lg:w-1/2 lg:py-24 lg:px-12"
      >
        <div class="xl:max-w-lg xl:ml-auto">
          <img class="h-10" src="/img/logo.png" alt="carbon logo" />
          <img
            class="mt-6 rounded-lg shadow-2xl sm:mt-8 sm:h-64 sm:w-full sm:object-cover sm:object-center lg:hidden"
            src="/img/chill.jpg"
            alt="woman on a swing"
          />
          <h1
            class="mt-6 text-2xl w-3/4 font-bold text-gray-900 leading-tight sm:text-4xl sm:mt-8 lg:text-3xl xl:text-4xl"
          >
            Chopping on the
            <span class="text-indigo-800"><i>Carbon</i> </span> side of life
          </h1>
          <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">
            Accessing financial services all day long.
          </p>
          <div class="mt-4 sm:mt-6">
            <a href="#" class="btn btn-indigo shadow-lg sm:text-base"
              >Get Carbon</a
            >
            <a href="#" class="ml-2 btn btn-gray sm:text-base">Learn more</a>
          </div>
        </div>
      </div>
      <div class="hidden lg:block lg:w-1/2 lg:relative">
        <img
          class="absolute inset-0 h-full w-full object-cover object-center"
          src="/img/chill.jpg"
          alt="woman on a swing"
        />
      </div>
      </div>
      <div>
        <div
          class="max-w-md sm:max-w-xl lg:max-w-6xl mx-auto px-8 lg:px-12 py-8"
        >
          <h2 class="text-xl text-gray-900">Carbon Locations</h2>
          <p class="text-gray-600">
            A list of all carbon locations present and future.
          </p>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'app',
    components: {},
    data() {
        return {
          officeLocations: [
            {
              city: "Lagos",
              staffCount: 120,
              deaptCount: 56,
              depts: ["ALL"],
              imageUrl: "/img/lagos.jpg",
              imageAlt: "Lagos Skyline"
            },
            {
              city: "Owerri",
              staffCount: 120,
              deaptCount: 56,
              depts: ["CS", "DS"],
              imageUrl: "/img/owerri.jpg",
              imageAlt: "Owerri Location"
            },
            {
              city: "Nairobi",
              staffCount: 120,
              deaptCount: 56,
              depts: [],
              imageUrl: "/img/nairobi.jpg",
              imageAlt: "Abuja Central"
            },
            {
              city: "Kano",
              staffCount: 120,
              deaptCount: 56,
              depts: [],
              imageUrl: "/img/kano.jpg",
              imageAlt: "Kano Hills"
            }
          ]
        };
      }
}
</script>

<style src="./assets/tailwind.css"></style>
