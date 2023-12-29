<template>
  <header class="bg-white shadow-md h-16 flex justify-between item-center">
    <router-link
      :to="{ name: home }"
      class="inline-flex items-center h-full px-5"
    >
      Home
    </router-link>
    <div class="flex items-center gap-1">
      <router-link
        :to="{ name: 'byName' }"
        class="inline-flex items-center h-full px-2 transition-colors hover:bg-purple-100"
      >
        Search Meal
      </router-link>
      <router-link
        :to="{ name: 'byLetter' }"
        class="inline-flex items-center h-full px-2 transition-colors hover:bg-purple-100"
      >
        Meal By Letter
      </router-link>
      <router-link
        :to="{ name: 'ingredients' }"
        class="inline-flex items-center h-full px-2 transition-colors hover:bg-purple-100"
      >
        Meal by Ingredients
      </router-link>
    </div>
  </header>
</template>
<script></script>
