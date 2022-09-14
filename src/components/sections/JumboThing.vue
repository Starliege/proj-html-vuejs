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
        width: 60%;
        height: 400px;
        z-index: 1;
        background: red;
        opacity: 0.9;
        display: flex;

        ul {
            list-style-type: none;
            margin: auto;

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
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    border-top: 400px solid white;
    border-left: 200px solid red;
    opacity: 1;
}

.secondhalf {
    background-image: url(../../assets/img/valentine.jpg);
    height: 400px;
    position: absolute;
    top: 0px;
    left: 49%;
    width: 55%;
    z-index: 0;
    border-radius: 5px;

}
</style>