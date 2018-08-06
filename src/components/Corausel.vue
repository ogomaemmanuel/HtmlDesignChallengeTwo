<template>
    <div>
        <div class="slider-section">
            <div class="grid-container">

                <div class="div grid-x slider-content">
                    <div class="cell large-4">
                        <h4>
                            Empowering Investors to Discover and exploit the vast potential for weath creation in Africa.
                        </h4>

                        <button>
                            Find out more   <i class="fa fa-angle-right"></i>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        data() {
            return {}
        }
    }
</script>
<style lang="scss" scoped>
    @import "styles/variables";
    @import "styles/mixins/mixins";
    .slider-section {
        background-image: url('../assets/CorauselBackground.png');
        background-size: cover;
        color: white;
        padding-bottom: 32px;
        padding-top: 32px;
        .slider-content{
            padding-top: 150px;
            height: 573px;

        }
        button {
            @include button
        }


    }
</style>
