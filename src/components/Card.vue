<script setup>
import arow1 from '../images/arow1.png';
import arow2 from '../images/arow2.png';
import arow3 from '../images/arow3.png';
import arow4 from '../images/arow4.png';
import arow5 from '../images/arow5.png';

const products = [
  { id: 1, name: 'Product 1', price: 19.99, image: arow1 },
  { id: 2, name: 'Product 2', price: 19.99, image: arow2 },
  { id: 3, name: 'Product 3', price: 19.99, image: arow3 },
  { id: 4, name: 'Product 4', price: 19.99, image: arow4 },
  { id: 5, name: 'Product 5', price: 19.99, image: arow5 }
];
</script>

<template>
  <div class="flex flex-col items-center">
    <h1 class="text-5xl font-bold mt-8 mb-4">გალერეა</h1>
    <div class="flex justify-center space-x-4">
      <div v-for="product in products" :key="product.id" class="border-none p-4">
        <img :src="product.image" :alt="product.name" class="max-w-full h-auto">
        <div class="mt-4">
          <h3 class="text-lg font-bold">{{ product.name }}</h3>
          <p class="text-gray-500">Price: ${{ product.price.toFixed(2) }}</p>
          <button class="bg-blue-500 text-white px-4 py-2 mt-2 rounded">Buy Now</button>
        </div>
      </div>
    </div>
  </div>
</template>


