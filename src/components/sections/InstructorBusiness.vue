<template>
    <div class="container">
        <div class="box">
            <div class="imgcon">
                <img src="../../assets/img/image_box_1-221x231.png" alt="">
            </div>
            <div class="txtcon">
                <h1>Become an Instructor</h1>
                <p>Teach what you love. Masterstudy gives you the tools to create a course.</p>
                <a href="">START TEACHING</a>
            </div>
        </div>
        <div class="box">
            <div class="imgcon">
                <img src="../../assets/img/image_box_2-234x231.png" alt="">
            </div>
            <div class="txtcon">
                <h1>Access For Business</h1>
                <p>Get unlimited access to 2,500 of top courses for your team.</p>
                <a href="">DOING BUSINESS</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "InstructorBusiness",
    };
</script>

<style lang="scss" scoped>
    .container {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        height: 530px;

        .box {
            width: 850px;
            height: 380px;
            border: 1px solid lightgray;
            margin-right: 30px;
            display: flex;
            align-items: center;

            .imgcon {
                width: 300px;

                img {
                    padding-left: 50px;
                }
            }

            .txtcon {
                width: 380px;
                padding-left: 40px;

                h1 {
                    font-size: 40px;
                    margin-top: -30px;
                }
                p {
                    font-size: 21px;
                    margin-bottom: 50px;
                }
                
                a {
                    border-radius: 35px;
                    background: #ff4450;
                    padding: 20px;
                    width: 250px;
                    height: 150px;
                    text-decoration: none;
                    color: white;
                }
                a:hover {
                    background: #46af35;
                    transition: 0.2s;
                }
            }
        }
    }
</style>