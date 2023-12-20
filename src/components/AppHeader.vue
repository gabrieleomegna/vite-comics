<script>
export default {
    
}
</script>

<template lang="">
    <header>
        <div class="container">
            <div class="logo">
            Immagine 
            </div>
            <nav>
                <ul class="hdr-nav-bar">
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    @use '../style/partials/mixins' as *;
    
    header {
        padding: 2rem;
        div.container {
        @include flex(row, space-between, center);
        .hdr-nav-bar{
            list-style: none;
            @include flex(row, space-around, center);
            
            li {
                text-transform: uppercase;
                margin-left: 1rem;
                font-weight: 600;
                font-size: .8rem;
            }
        }
    }
    } 
    



</style>