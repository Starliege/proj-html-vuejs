<template>
    <div class="container">
        <div class="news">
            <div class="subtxt">
                <h2>Subscribe our newsletter</h2>
                <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>
            </div>
            <div class="emailsub">
                <div style="display: block;">
                    <h6>YOUR E-MAIL ADDRESS</h6>
                </div>
                <div style="display: flex;">
                    <input type="text">
                    <button>SUBSCRIBE</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "NewsLetter",
    };
</script>

<style lang="scss" scoped>
    .container {
        background-color: #ff4550;
        height: 170px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        color: white;

        .news {

            display: flex;
            justify-content: center;
            align-items: center;

            .subtxt {
                width: 680px;
                margin-right: 30px;
            }

            h6 {
                margin-top: 0;
                margin-bottom: 10px;
                font-size: 16px;
                
            }

            .emailsub {

                input {
                    width: 350px;
                    height: 45px;
                    display: inline;
                }

                button {
                    width: 140px;
                    height: 50px;
                }
            }
        }

    }
</style>