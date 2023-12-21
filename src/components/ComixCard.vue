<template>
    <article class="comix-card">
        <img :src="comixThumb" alt="Comix image">
        <p>
            {{ comixSeries }}
        </p>
    </article>
</template>
<script>
export default {
    name: 'ComixCard',
    props: [
        'comixThumb',
        'comixSeries',
    ]
}
</script>
<style lang="scss" scoped>
    article.comix-card {
        width: calc((100% / 6) - 1.5rem);
        // background-color: blue;
        margin-right: .75rem;
        margin-bottom: 3rem;
        height: 200px;
        img{
            width: 100%;
            height: 80%;
            margin-bottom: 1rem;
        }
        p{
            font-size: .7rem;
            text-transform: uppercase;
        }
    }
</style>