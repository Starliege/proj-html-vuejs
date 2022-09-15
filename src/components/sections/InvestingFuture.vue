<template>
    <div class="container">
        <div class="box">
            <div class="maintxt">
                <h1>Paints of the Future</h1>
                <p>The response to your MasterStudy has been really overwhelming! 
                    Those who participated in the workshop are spreading the word here on campus and the “buzz” is on. The VP of Instruction wants you to come back! 
                    Her goal is to have more faculty trained. She also wants to attend a workshop herself. 
                    Our President told me Masterstudy needs to be the cornerstone of our success program.”</p>
            </div>
            <div class="dude">
                <h4>Xatashi Froust</h4>
                <p>SEO, Froust Inc</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "InvestingFuture",
    };
</script>

<style lang="scss" scoped>
    .container {
        height: 670px;
        background-image: url(../../assets/img/micah-296507-unsplash-1-copy-1-1920x700-1-1917x699.jpg);
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;

        .box {
            width: 740px;
            height: 530px;
            background-color: white;
            margin-left: -400px;
            
            .maintxt {
                padding: 80px 80px 0 80px;

                h1 {
                    font-size: 42px;
                }

                p {
                    font-size: 24px;
                }
            }
            .dude {
                padding: 0 80px 80px 80px;
                
                h4 {
                    font-size: 20px;
                    margin-bottom: -15px;
                }
            }
        }
    }
</style>