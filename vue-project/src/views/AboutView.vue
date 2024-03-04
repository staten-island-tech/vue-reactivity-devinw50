<template>
    <div>
      <h2>Cart</h2>
      <ul>
        <li v-for="(item, index) in cart" :key="index">
          {{ item.name }} - ${{ item.price }}
        </li>
      </ul>
    </div>
  </template>
  
  <script setup>
  import { cart } from "@/cart";
  </script>
  
  <style scoped>
  /* Your styles */
  </style>
  