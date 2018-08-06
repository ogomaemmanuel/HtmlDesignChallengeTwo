<template>
    <div>
        <div class="highlights-section">
            <div class="grid-container">
                <div class="grid-x grid-margin-x">
                    <div class="cell large-4 small-12 medium-4">
                        <div class="stock-brockarage">
                            <h3>Stock Brokerage</h3>
                            AIB has appointed securities representatives and Investors' agents countrywide to extend its reach.
                            Such agents and repreantatives have undergone appropriate training on how to approach and assist prospective investor
                            <button>Find out more <i class="fa fa-angle-right"></i></button>
                        </div>
                    </div>

                    <div class="cell large-4 small-12 medium-4">
                        <div class="online-trading">
                            <div class="content">
                                <h4>
                                    Mobile and Online Trading
                                </h4>
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
<style lang="scss" scoped>
    @import "styles/variables";
    @import "styles/mixins/mixins";
    .highlights-section {
        height: 400px;
        .stock-brockarage {
            padding-top: 40px;
            padding-left: 20px;
            padding-right: 20px;
            height: 303px;
            color: #ffffff;
            background-color: #6B1A3A;
            button {
               @include button;
            }
        }
        .online-trading {
            margin-top: 0px;
            height: 303px;
            position: relative;
            background-image: url("../assets/mobileTrading.jpg");
            .content {
                margin-left: 40px;
                color: #ffffff;
                position: absolute;
                bottom: 0;
                left: 0;
            }
        }
    }
</style>

