<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  @apply text-gray-800;
  @apply flex;
  @apply flex-col;
  @apply items-center;
  @apply text-center;
}

#nav {
  @apply p-8;
}

#nav a {
  @apply font-bold;
  @apply text-gray-800;
}

#nav a.router-link-exact-active {
  @apply text-green-500;
}
</style>
