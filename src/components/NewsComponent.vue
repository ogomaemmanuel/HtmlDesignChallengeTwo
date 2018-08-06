<template>
    <div>
            <div class="news-article-section">
                <div class="head-section">
                    <div class="grid-container">
                    <h4>Revised AIB Account Maintannce And Tarris Fees</h4>
                    </div>
                </div>
                <div class="body-section">
                    <div class="grid-container">
                   <p>We have reviewed our fee tarrifs and Introduced account Maintance fee In effort</p>
                    </div>
                </div>
                <div class="publication-details">
                    <div class="grid-container">
                    <p>Written on Thursday,31 July 2014 06:06</p>
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
    .news-article-section {
        height: 300px;
        position: relative;
        background-color: #FFFFFF;
        .head-section {
            background-color: #4F132C;
            position: relative;
            height: 125px;
            color: #ffffff;
            h4{
                position: absolute;
                top: 30%;

            }
        }

        .body-section {
            margin-top: 5%;

        }

        .publication-details {
            background-color: #ffffff;
            position: absolute;
            text-align: right;
            bottom: 0px;
            right: 0px;
        }

    }


</style>