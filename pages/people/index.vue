<template>
  <div>
    <div v-if="$route.params.id">
      <h1 v-text="'Nama: Muhammad Amien, id: ' + $route.params.id"></h1>
    </div>

    <div v-else>
      <h1>List People</h1>
      <ul>
        <li>
          <nuxt-link to="/people/12">People:12</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/people/1">People:1</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/people/4">People:4</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/people/5">People:5</nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>