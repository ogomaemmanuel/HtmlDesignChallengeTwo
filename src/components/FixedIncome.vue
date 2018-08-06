<template>
    <div>
        <div class="fixed-income-section">
            <div class="grid-x">
                <div class="cell large-offset-6 large-4 small-12 medium-4">
                    <div class="fixed-income-overlay">
                        <div class="grid-x grid-margin-x">
                            <div class="cell large-7 small-12 medium-7">

                                <h4>Fixed Income Securities</h4>
                                <p>
                                    We shall seek to find and retain people who are passionate about
                                    a greator cause and empower them to fullfill their dreams.

                                    <button>
                                        Find out more <i class="fa fa-angle-right"></i>
                                    </button>
                                </p>
                            </div>
                        </div>
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
<style scoped lang="scss">
    @import "styles/variables";
    @import "styles/mixins/mixins";
    .fixed-income-section {
        position: relative;
        height: 435px;
        background-image: url("../assets/FixedIncome.jpg");
        .fixed-income-overlay {
            position: absolute;
            margin-top: 137px;
            color: #ffffff;
            .cell {
                padding-top: 22px;
                padding-left: 20px;
                padding-right: 20px;
                background-color: rgba(68, 20, 49, 0.6);
                border-top-width: 3px;
                border-top-color: $button-color;
                border-top-style: solid;
                button{
                    @include button;
                }
            }
        }
    }
</style>