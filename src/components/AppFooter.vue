<script>
    import UpperFooter from './UpperFooter.vue';
    import BottomFooter from './BottomFooter.vue';
    export default {
        name : 'AppFooter',
        components: {
            UpperFooter,
            BottomFooter,
        }
    }
</script>


<template lang="">
    <footer>
        <UpperFooter/>
        <BottomFooter/>
    </footer>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;

    footer{
        color: $main-content-color;
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
    }
</style>