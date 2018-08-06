<template>

    <div>
        <div class="site-map-section">
            <div class="grid-container">
            <div class="grid-x content small-up-1 medium-up-3 large-up-3">
                <div class="cell">
                    <div class="grid-x grid-padding-x small-up-12 medium-up-12 large-up-12">
                        <h6 class="cell">Our  Business</h6>
                        <a class="cell" href="#">About</a>
                        <a class="cell" href="#">Partners</a>
                        <a class="cell" href="#">Our Values</a>
                        <a class="cell" href="#">Time Line</a>
                        <a class="cell" href="#">Videos</a>
                        <h6 class="cell">For Apartments</h6>
                        <a class="cell" href="#">Living Spaces</a>
                    </div>
                </div>
                <div class="cell">

                    <div class="grid-x grid-padding-x small-up-12 medium-up-12 large-up-12">
                        <h6 class="cell">Our  Research</h6>
                        <a class="cell" href="#">About</a>
                        <a class="cell" href="#">Partners</a>
                        <a class="cell" href="#">Our Values</a>
                        <a class="cell" href="#">Time Line</a>
                        <a class="cell" href="#">Videos</a>
                        <h6 class="cell">For Apartments</h6>
                        <a class="cell" href="#">Living Spaces</a>
                    </div>


                </div>

                <div class="cell">
                    <div class="grid-x grid-padding-x small-up-12 medium-up-12 large-up-12">
                        <div class="background-logo cell">

                        </div>
                        <div class="simple-subscription-form cell">
                            <form>
                                <div class="input-group">
                                    <label>Subccribe to our reports
                                    <input placeholder="Input email address" class="input-group-field"  type="email">
                                    </label>
                                    <label>
                                        <button type="submit" class="button"><i class="fa fa-arrow-circle-right"></i></button>
                                    </label>
                                </div>
                            </form>
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
        data(){
            return{

            }
        }
    }
</script>
<style lang="scss">
    @import "styles/variables";
    .site-map-section{
        color: white;
        .background-logo{
            height: 100px;
            width: 250px;
            background-image: url("../assets/Logo.png");
            background-size: cover;
            background-position: center center ;
            float: right;

        }

        .content{
            padding-top: 40px;
            background-color: rgba(0, 0, 0, 0.1);
            border-top-style: solid;
            border-top-color: #414141;
            border-top-width: 1px;
            padding-bottom: 40px;

        }
        background-color: rgba(0, 0, 0, 1);
        h6{
            color:#ffffff;
        }
        h4{
            color:#ffffff;
        }
        a{
            color: #F2F2F2;
        }
        label{
            color: white;
        }
        input{
            background-color: #1A1A1A;
            border-style: none;
            color: #757575;
        }
        button.button {
            margin-top: 24px;
            background-color: $button-color;
        }
    }
</style>