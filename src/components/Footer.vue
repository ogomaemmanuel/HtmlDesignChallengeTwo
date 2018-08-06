<template>
    <div>
        <div class="footer-section">

        </div>
        <footersociallinks></footersociallinks>
        <footersitemap></footersitemap>
        <footercopyright></footercopyright>
    </div>

</template>

<script>
    import footersociallinks from "./FooterSocialLinks.vue"
    import footersitemap from "./FooterSiteMap.vue"
    import footercopyright from "./FooterCopyRight.vue"
    export default {
        components:{
            footersociallinks,
            footersitemap,
            footercopyright
        },
        data(){
            return{

            }
        }
    }
</script>
<style scoped lang="scss">
    .footer-section{
        background-color: black;
    }

</style>