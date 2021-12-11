<template>
<Hero></Hero>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Hero from "@/components/Hero.vue"

export default defineComponent({
  name: 'Home',
  components: {
    Hero
  },
    watch: {
        $route: {
            immediate: true,
            handler(to, from) {
                document.title = "FeedTo | Home" || 'Feedto';
            }
        },
    }
});
</script>
