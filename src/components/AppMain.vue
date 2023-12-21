<script>
export default {
    name : 'AppMain',
}
</script>

<template lang="">
    <main>
        <div class="container">
            <h1> Content goes here</h1>
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