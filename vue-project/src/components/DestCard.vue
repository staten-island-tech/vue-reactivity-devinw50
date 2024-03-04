<template>
  <div class="dest-card">
    <img :src="destination.img" :alt="destination.name" />
    <h3>{{ destination.name }}</h3>
    <p>Price: ${{ destination.price }}</p>
    <button @click="addToCart">Add to Cart</button>
  </div>
</template>

<script setup>
import { defineProps, defineEmits } from 'vue';

const props = defineProps({
  destination: Object
});

const emits = defineEmits(['addToCart']);

function addToCart() {
  emits('addToCart', destination); // Emit the event with destination as argument
}
</script>

<style scoped>
.dest-card {
  padding: 10px;
  width: 200px;
  align-items: center;
}

.dest-card img {
  width: 100%;
}

.dest-card button {
  margin-top: 10px;
}
</style>
