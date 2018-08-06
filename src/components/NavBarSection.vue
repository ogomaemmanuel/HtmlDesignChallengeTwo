<template>
    <div>
        <div class="navbar-section">
            <div class="grid-container">
                <div class="top-bar" id="responsive-menu">
                    <div class="logo">
                        <img src="../assets/Logo.png" alt="">
                    </div>
                    <div class="top-bar-right">
                        <ul class="menu align-center">
                            <li><a href="#">The Company</a></li>
                            <li><a href="#">Our Team</a></li>
                            <li><a href="#">Our Solutions</a></li>
                            <li><a href="#">Media</a></li>
                            <li><a href="#">Contact</a></li>
                            <li><a href="#"><i class="fa fa-search"></i></a></li>
                        </ul>
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

    .navbar-section {

        #responsive-menu {
            height: 70px;
            background-color: #ffffff;
        }
        .menu {
            padding-top: 17px;
            text-align: center;
            height: 70px;
            background-color: #ffffff;
            li {
                a {
                    color: #732443;
                }
                &:hover {
                    border-bottom-style: solid;
                    border-bottom-color: $button-color;
                }
            }
        }

    }

</style>