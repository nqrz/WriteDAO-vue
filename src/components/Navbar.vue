<template>
  <div class="border-b-2 border-slate-300">
    <div class="container">
      <div class="flex justify-between w-full">
        <router-link to="/" class="navbar-link gap-2">
          <img src="../assets/logo-light-16x16.png" alt="Logo Nizar Baihaqi">
          Home
        </router-link>
        <p class="py-2">
          WriteDAO
        </p>
        <router-link to="/about" class="navbar-link">
          About
        </router-link>
      </div>
    </div>
  </div>
</template>

<style scoped>

.navbar-link {
  @apply py-2 px-3 hover:bg-slate-300
}

</style>
