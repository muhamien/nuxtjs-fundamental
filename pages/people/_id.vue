<template>
  <div>
    <div v-if="$route.params.id">
      <h1 v-text="'Nama: Muhammad Amien, id: ' + $route.params.id"></h1>
      <nuxt-link to="/people">back</nuxt-link>
    </div>

    <div v-else>
      <h1>List People</h1>
    </div>
  </div>
</template>