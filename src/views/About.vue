<template>
<div></div>
</template>

<script lang="ts">
export default {
    name: 'About',
    watch: {
        $route: {
            immediate: true,
            handler(to, from) {
                document.title = 'FeedTo | About';
            }
        },
    }
};

</script>
