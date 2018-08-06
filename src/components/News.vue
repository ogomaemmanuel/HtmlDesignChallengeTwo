<template>
    <div>


        <div class="news-section">

            <div class="grid-container">
                <div class="grid-x">
                <div class="cell small-12 large-6 header">
                    <h3>IN THE NEWS</h3>
                </div>

                <div class="cell content-right small-12 large-6 header">
                    <button>View More  <i class="fa fa-angle-right"></i></button>
                </div>
                </div>
            </div>
            <div class="grid-container new-content">
                <div class="">

                    <div class="grid-x grid-margin-x">
                        <div class="cell large-4 small-12 medium-4">
                            <newscomponent></newscomponent>
                        </div>
                        <div class="cell large-4 small-12 medium-4">
                            <newscomponent></newscomponent>
                        </div>
                        <div class="cell large-4 small-12 medium-4">
                            <newscomponent></newscomponent>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    import newscomponent from "./NewsComponent.vue"

    export default {
        components: {
            newscomponent
        },
        data() {
            return {}
        }
    }

</script>
<style scoped lang="scss">
    @import "styles/variables";
    .news-section {
        background-color: #F7F7F7;
        height: 450px;
            .content-right{
                text-align: right;
                margin-top: auto;
                margin-bottom: auto;
                button{
                    background-color: #DBDBDB;
                    width: 140px;
                    height: 43px;
                    color: #7D7D7D;
                }
        }
    }
</style>