<template>
    <div class="container">
        <div class="topbar">
            <div class="lang" style="align-self: center;">
                English <img class="arrow" src="../../assets/img/icons/down-arrow-svgrepo-com.svg" alt="">
            </div>
            <div class="topnavbar">
                <ul>
                    <li>Home</li>
                    <li>Pages</li>
                    <li>Course Formats</li>
                    <li>Courses</li>
                    <li>Demos</li>
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
    };
    </script>
    

<style lang="scss">
    body {
        margin: 0 auto;
    }
    .container {
        border-bottom: solid 1px lightgray;
        color: gray;
        font-size: 14px;

        .topbar {
            display: flex;
            justify-content: space-between;
            height: 25px;
            margin-right: 5%;
            margin-left: 5%;
            margin-bottom: 20px;
            align-items: center;
            
            .lang {
                margin-top: 20px;

                img {
                    filter: grayscale(100%);
                }
            }

            .topnavbar {
                display: flex;
                align-items: center;
                margin-top: 20px;

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