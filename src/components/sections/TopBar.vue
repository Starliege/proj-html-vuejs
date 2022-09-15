<template>
    <div class="container">
        <div class="topbar">
            <div class="lang" style="align-self: center;">
                English <img class="arrow" src="../../assets/img/icons/down-arrow-svgrepo-com.svg" alt="">
            </div>
            <div class="topnavbar">
                <ul>
                    <li v-for="nav in navs" :key="nav.navver">{{ nav.navver }}</li>
                </ul>
                <ul>
                    <li class="icon"><img src="../../assets/img/icons/fb.svg" alt=""></li>
                    <li class="icon"><img src="../../assets/img/icons/twt.svg" alt=""></li>
                    <li class="icon"><img src="../../assets/img/icons/ig.svg" alt=""></li>
                    <li class="icon"><img src="../../assets/img/icons/ln.svg" alt=""></li>
                    <li class="icon"><img src="../../assets/img/icons/g.svg" alt=""></li>
                    <li class="icon"><img src="../../assets/img/icons/yt.svg" alt=""></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
      name: "TopBar",
      data (){
        return {
            navs: [
                {navver: 'Home'},
                {navver: 'Pages'},
                {navver: 'Course Formats'},
                {navver: 'Courses'},
                {navver: 'Demos'}
            ]
        }
  }
}
    </script>
    

<style lang="scss" scoped>
    .container {
        border-bottom: solid 1px lightgray;
        color: gray;
        font-size: 14px;

        .topbar {
            display: flex;
            justify-content: space-between;
            height: 55px;
            margin-right: 6%;
            margin-left: 6%;
            align-items: center;

            .topnavbar {
                display: flex;
                align-items: center;
                

                ul {
                    list-style-type: none;
                    margin: auto ;
                    display: inline;

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
        .arrow {
            height: 12px;
            margin-left: 5px;
        }
    }

    
</style>