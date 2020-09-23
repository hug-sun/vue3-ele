<template>
  <header></header>
  <router-view></router-view>
  <ul></ul>
</template>

<script>
import { useRoute, useRouter } from 'vue-router';
export default {
  setup() {
    const route = useRoute();
    const router = useRouter();
    console.log(route, 'route');
    console.log(router, 'router');
  }
};
</script>
