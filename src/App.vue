<template>
  <Header />
  <div class="container">
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Header from '@/components/Header.vue'; // @ is an alias to /src

export default defineComponent({
  components: {
    Header
  },
});
</script>


