<script>
    export default {
        name: 'UpperFooter',        
    }
</script>

<template lang="">
    <section id="upper-footer">
        <div class="container">
            <article class="ftr-list-box">
                <ul class="ftr-list">
                    <li class="list-title"><h3>Lorem</h3></li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                </ul>
                <ul class="ftr-list">
                    <li class="list-title"><h3>Lorem</h3></li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                </ul>
            </article>
            <article class="ftr-list-box">
                <ul class="ftr-list">
                    <li class="list-title"><h3>Lorem</h3></li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                </ul>
            </article>
            <article class="ftr-list-box">
                <ul class="ftr-list">
                    <li class="list-title"><h3>Lorem</h3></li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                    <li>Lorem</li>
                </ul>
            </article>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    @use '../style/partials/mixins' as *;
    section#upper-footer{
        background-image: url('../assets/img/footer-bg.jpg');
    }
    .container {
        padding: 2rem 0;
        @include flex (row, start, stretch);
        article.ftr-list-box{
            margin-right: 4rem;
            
            &:first-of-type ul:nth-child(2){
                margin-top: 1rem;
            }
            ul.ftr-list {
                list-style-type: none;
                .list-title{
                    margin-bottom: .7rem;
                }
                li:not(.list-title) {
                    margin-bottom: .35rem;
                    opacity: .5;
                    font-size: .7rem;
                    font-weight: 100;
                }
            }
        }
    }

</style>