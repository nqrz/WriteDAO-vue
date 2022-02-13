<script setup>
import Navbar from './components/Navbar.vue';
</script>

<template>
  <div>
    <Navbar />
    <router-view />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Noto Sans', sans-serif;
  margin: 0;
  padding: 0;
}

.tooltip {
  position: fixed;
  top: 0;
  right: 0;
  display: flex;
  gap: 10px;
  margin-right: 10px;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.bg-banner {
  background-image: linear-gradient(to bottom left, whitesmoke, lightblue);
}

.link {
  text-decoration: none;
}

.btn {
  border: none;
  margin-top: 10px;
  padding: 10px;
  padding-top: 8px;
  padding-bottom: 8px;
  border-radius: 4px;
  display: flex;
  align-items: center;
}

.btn:hover {
  cursor: pointer;
}
</style>
