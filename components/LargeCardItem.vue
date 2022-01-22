<template lang="">
  <div class="flex justify-center">
    <div class="rounded-lg bg-white max-w-sm">
      <a href="#!">
        <img
          class="rounded-lg"
          :src="require(`~/assets/img/${data.image || 'roomba-1.jpg'}`)"
          alt="featured-product"
        />
      </a>
      <div class="py-6">
        <h5 class="text-gray-900 text-xl font-medium mb-2">
          {{ data.title }}
        </h5>
        <p class="text-gray-500 text-base mb-4">
          {{ data.description }}
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    data: {
      type: Object,
      default() {
        return {
          title: '',
          description: '',
          image: '',
        }
      },
    },
  },
}
</script>
<style lang=""></style>
