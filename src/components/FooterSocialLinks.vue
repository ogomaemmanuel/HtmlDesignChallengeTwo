<template>
    <div>

            <div class="social-links">
                <div class="grid-container">
                <div class="grid-x">
                    <div class="cell small-1"><h4>Social</h4></div>
                    <div class="cell small-1"><i class="fa fa-facebook fa-2x"></i></div>
                    <div class="cell small-1"><i class="fa fa-twitter fa-2x"></i></div>
                    <div class="cell small-1"><i class="fa fa-instagram fa-2x"></i></div>
                    <div class="cell small-1"><i class="fa fa-linkedin fa-2x"></i></div>

                    <div class="cell contact small-7"><span><p>Sales Enquiries - +254720220178/2212206</p></span></div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        data(){
            return{

            }
        }
    }
</script>
<style lang="scss">
    @import "styles/variables";
    .social-links{
        color: #ffffff;
        padding-top: 40px;
        background-color: #000000;
        p{
            color: $button-color;
        }
        height: 135px;
        .contact{
            text-align: right;

        }
        i
        {
            border-radius: 50%;
            border: 1px solid #353535;
            padding:10px;
            color: #353535;
        }
    }
</style>