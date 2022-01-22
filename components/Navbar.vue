<template lang="">
  <nav class="flex items-center justify-between flex-wrap bg-blue-500 p-5">
    <div class="flex items-center">
      <img src="~/assets/img/logo.png" alt="logo" class="h-7 mr-10" />
      <div class="hidden lg:block text-gray-300">
        <a href="#" class="text-white hover:text-white mr-2"> Home </a>
        <a href="#" class="hover:text-white mr-2"> Products </a>
        <a href="#" class="hover:text-white mr-2"> About </a>
        <a href="#" class="hover:text-white mr-2"> Contact </a>
      </div>
    </div>
    <div class="hidden lg:block">
      <a href="" class="text-gray-200 hover:text-white mr-3">Register</a>
      <a
        href=""
        class="w-full rounded-full px-4 py-1 bg-white hover:bg-gray-100 text-sm font-semibold cursor-pointer"
      >
        Log In
      </a>
    </div>

    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-white border-white"
      >
        <font-awesome-icon icon="bars"></font-awesome-icon>
      </button>
    </div>
  </nav>
</template>
<script>
export default {
  //
}
</script>
