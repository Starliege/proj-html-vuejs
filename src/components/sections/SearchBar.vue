<template>
  <div class="container">
      <div class="topbar">
          <div class="lang" style="align-self: center;">
              <img src="../../assets/img/MasterStudy.svg" alt="" style="height: 45px;">
          </div>
          <div class="MiddleSearch">
            <span style="margin-right: 20px;">Category</span>
            <input type="text" class="SearchBar">
            <button class="SearchButton"></button>
          </div>
          <div class="RightSearch">
              <ul>
                  <li>Become an Instructor</li>
                  <li>For Enterprise</li>
                  <li>Log in</li>
                  <li><a href="">SIGN UP</a></li>
                  <li>heart</li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>
  export default {
    name: "SearchBar",
  };
  </script>
  

<style lang="scss" scoped>
  .container {
      font-size: 14px;

      .topbar {
          display: flex;
          justify-content: space-between;
          height: 105px;
          margin-right: 6%;
          margin-left: 6%;
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
      
      .arrow {
          height: 12px;
          margin-left: 5px;
      }

      .MiddleSearch{
        display: flex;
        align-items: center;
      }

      .SearchBar{
        width: 600px;
        height: 45px;
      }

      .SearchButton {
        width: 60px;
        height: 50px;
      }
  }

  
</style>