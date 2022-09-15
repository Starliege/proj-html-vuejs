<template>
    <div class="container">
        <div class="textbox">
            <h1>Limitless learning,
                more possibilities
            </h1>
            <span style="display: block; font-size: 24px; margin-bottom: 40px;">
                Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.
            </span>
            <a href="">Read more</a>
        </div>
    </div>
</template>

<script>
    export default {
    name: "PostJumbo",
    };
</script>

<style lang="scss" scoped>
    .container {
        height: 530px;
        background-image: url(../../assets/img/bg.png);
        margin-bottom: 110px;

        .textbox {
            padding-left: 400px;
            padding-top: 100px;
            width: 600px;

            h1 {
                font-size: 48px;
                width: 400px;
            }
        }
    }
</style>