<template>
    <div class="container">
        <div class="jumbo">
            <div class="firsthalf">
                <ul>
                    chiacchiere
                </ul>
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
.jumbo {
    position: relative;

    .firsthalf {
        position: absolute;
        width: 50%;
        height: 400px;
        z-index: 1;
        background: red;
        opacity: 1;
        display: flex;

        ul {
            list-style-type: none;
            margin: auto;
            z-index: 5;

            li {
                display: inline;
                margin-right: 20px;

                img {
                    height: 17px;
                    align-self: center;
                    filter: grayscale(100%);
                }
            }
        }
    }
}

.firsthalf::before {
    content: "";
    position: absolute;
    width: 0;
    height: 0;
    border-bottom: 400px solid red;
    border-right: 200px solid transparent;
    border-left: 980px solid red;
}

.secondhalf {
    background-image: url(../../assets/img/valentine.jpg);
    height: 400px;
    position: absolute;
    top: 0px;
    left: 49%;
    width: 100%;
    z-index: 0;
    border-radius: 5px;

}
</style>