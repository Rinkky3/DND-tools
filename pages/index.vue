<template>
  <main>
    <ul>
      <li
        v-for="page in ['Options API', 'Class API', 'Composition API']"
        :key="page"
      >
        <nuxt-link :to="`/${page.toLowerCase().split(' ').join('-')}`">
          With gay {{ page }}
        </nuxt-link>
      </li>
    </ul>
  </main>
</template>

<script lang="ts">
</script>
