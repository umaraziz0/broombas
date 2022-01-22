<template>
  <div>
    <Navbar />
    <Hero />
    <Logos />
    <LargeCardDisplay :data="data[0]" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      data: [
        {
          title: 'Featured Products',
          description: 'Browse through our newest and most advanced products.',
          items: [
            {
              title: 'Roomba 001',
              description: 'Voluptatem in dolor ut et.',
              image: 'roomba-1.jpg',
            },
            {
              title: 'Roomba 002',
              description:
                'Eveniet nemo nobis sunt minima esse recusandae similique esse cum.',
              image: 'roomba-2.jpg',
            },
            {
              title: 'Roomba 003',
              description:
                'Quia libero hic reiciendis est molestias nostrum. A sint officia.',
              image: 'roomba-3.jpg',
            },
          ],
        },
      ],
    }
  },
}
</script>
