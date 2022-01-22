<template lang="">
  <div class="container items-center max-w-6xl px-8 my-20 mx-auto xl:px-5">
    <div class="text-center mb-8">
      <h3 class="font-bold text-2xl">
        {{ data.title }}
      </h3>
      <h4 class="text-lg text-gray-500">
        {{ data.description }}
      </h4>
    </div>
    <div class="grid grid-cols-3 gap-8">
      <div
        v-for="(item, index) in data.items"
        :key="index"
        class="col-span-3 lg:col-span-1"
      >
        <LargeCardItem :data="item" />
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
          items: [],
        }
      },
    },
  },
}
</script>
<style lang=""></style>
