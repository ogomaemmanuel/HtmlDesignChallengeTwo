<template>
    <div>
        <div class="fiduciacy-section">
            <div class="grid-container">
            <div class="grid-x">
                <div class="cell group-map large-6">
                    <img height="322" src="../assets/Group2.jpg" alt="">
                </div>
                <div class="cell fiduciacy-content large-3">
                  <h4>Our fiduciary responsibilities to our clients will always come first</h4>
                    <button>
                        Find Out more <i class="fa fa-angle-right"></i>
                    </button>
                </div>
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
    .fiduciacy-section{
        height: 322px;
        margin-top: 20px;
        margin-bottom: 58px;
        .group-map {
        }
        .fiduciacy-content{
            margin-left: 105px;
            padding-top: 70px;
            button{
                background-color: #000000;
                color: #ffffff;
                position: relative;
                width: 200px;
                height: 50px;
                color: #ffffff;
                padding-top: 5px;
                padding-bottom: 5px;
                margin-top: 20px;
            }
        }
    }
</style>