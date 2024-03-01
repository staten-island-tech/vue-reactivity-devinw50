<template>
  <div>
    <h2>{{ Destination.name }}</h2>
    <img :src="Destination.img" alt="" />
    <h3>{{ clicked }}</h3>
    <button id="addbtn" @click="increment">Add to Cart</button>
  </div>
</template>

<script setup>
const props = defineProps({
  Destination: Object,
});

</script>

<style scoped>
img {
  width: 240px;
  height: 240px;
  object-fit: cover;
  border: 5px;
  border-radius: 5%;
}

</style>