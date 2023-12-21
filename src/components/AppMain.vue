<script>
import ListComix from './ListComix.vue';
export default {
    name : 'AppMain',
    components : {
        ListComix,
    }
}
</script>

<template lang="">
    <main>
        <div class="container">
            <ListComix/>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;
    main {
        padding: 2rem 0;
        background-color: rgb(28, 28, 28);
        color: $main-content-color;
    }
</style>