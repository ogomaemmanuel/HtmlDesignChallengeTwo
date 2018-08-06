<template>
    <div>
        <nav_bar_section></nav_bar_section>
        <corausel></corausel>
        <ticker></ticker>
        <highlights></highlights>
        <news></news>
        <fixedIncome></fixedIncome>
        <fiduciary></fiduciary>
        <footer_section></footer_section>
    </div>
</template>
<script>
    import header_section from "./Header.vue"
    import nav_bar_section from "./NavBarSection.vue"
    import  corausel from  "./Corausel.vue"
    import highlights from "./Highlights.vue"
    import fixedIncome from "./FixedIncome.vue"
    import news from "./News.vue"
    import fiduciary from "./Fiduciary.vue"
    import footer_section from "./Footer.vue"
    import ticker from "./Ticker.vue"
    export default {
        components:{
            header_section,
            nav_bar_section,
            corausel,
            highlights,
            news,
            fixedIncome,
            fiduciary,
            footer_section,
            ticker
        },
        data(){
            return{

            }
        }
    }

</script>

<style scoped>


</style>