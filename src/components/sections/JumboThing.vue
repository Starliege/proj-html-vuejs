<template>
    <div class="container">
        <div class="jumbo">
            <div class="firsthalf">
                <div class="textbox">
                    <span style="display:block; text-align: center;">Become Udemy Affiliate</span>
                    Import Udemy courses to your website and earn commission on every sale!
                </div>
            </div>
            <div class="secondhalf">

            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: "JumboThing",
};
</script>
    
  
<style lang="scss" scoped>
.container {
    margin-bottom: 60px;

    .jumbo {
        position: relative;

        .firsthalf {
            position: absolute;
            width: 50%;
            height: 400px;
            z-index: 1;
            background: #ff4550;
            opacity: 1;
            display: flex;
            justify-content: center;

            .textbox {
                align-self: center;
                z-index: 5;
            }
        }
    }

    .firsthalf::before {
        content: "";
        position: absolute;
        width: 0;
        height: 0;
        border-bottom: 400px solid #ff4550;
        border-right: 200px solid transparent;
        border-left: 1200px solid #ff4550;
    }

    .secondhalf {
        background-image: url(../../assets/img/valentine.jpg);
        height: 400px;
        position: absolute;
        top: 0px;
        width: 100%;
        z-index: 0;
        border-radius: 5px;
    }
}
</style>