<template>
  <div>
    <nav class="flex-container align-middle padding-2">
        <nuxt-link :to="'game-board'">
            {{'Game board'}}
        </nuxt-link>
    </nav>
    <nuxt />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default class Baseview extends Vue {
    navlinks = [
        'game-board'
    ]
}
</script>
<style lang="scss">
@import '@/assets/app.scss';
</style>