<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptates
      nostrum nemo quo numquam quas nobis iure, est voluptatum deleniti
      praesentium?
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params
</script>

<style lang="scss" scoped></style>
