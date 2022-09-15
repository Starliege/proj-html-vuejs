<template>
    <div class="container">
        <div class="bar">
            <div class="about box">
                <h3>ABOUT</h3>
                <p>Sed nec felis pellentesque, lacinia dui sed, ultricies sapien. Pellentesque orci lectus, consectetur vel, rutrum eu ipsum. Mauris accumsan eros eget libero posuere vulputate.</p>
            </div>
            <div class="contact box">
                <h3>CONTACT</h3>
                <p>USA, Callifornia 20, First Avenue, Callifornia</p>
                <p>Tel.: +1 212 458 300 32
                   Fax: +1 212 375 24 14</p>
                <p style="color:gray;">info@masterstudy.com</p>
            </div>
            <div class="social box">
                <h3>SOCIAL NETWORK</h3>
                <img src="../../assets/img/94a89743db767254bbbd75b19692c582.png" alt="">
            </div>
            <div class="udemy box">
                <img src="../../assets/img/Top-udemy-courses-90-percent-off.jpg" alt="">
            </div>
        </div>
        <div class="copyright">
            <div style="margin-left: -750px;">
                <img src="../../assets/img/footer-logo2x-50x56.png" alt="">
                Copyright © 2022. <a href="">MasterStudy</a> Theme by <a href="">StylemixThemes</a>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
    .container {
        height: 300px;
        background-color: #273044;

        .copyright {
            height: 75px;
            background-color: #273044;
            border-top: 1px solid gray;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            color: white;

            div {
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            color: white;
            }

                a {
                    color: white;
                    margin-left: 2px;
                    margin-right: 2px;
                }

                img {
                    height: 30px;
                    margin-right: 20px;
                }
            }

        .bar {
            color: white;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            padding: 50px;

            .box {
            width: 240px;
            display: block;
            margin-right: 60px;
            }

            .udemy {
                
                img {
                    height: 170px;
                }
            }
        }
    }
</style>