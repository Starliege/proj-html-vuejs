<template>
  <div class="container">
      <div class="topbar">
          <div class="lang" style="align-self: center;">
              <img src="../../assets/img/MasterStudy.svg" alt="">
          </div>
          <div class="Searchbar">
            Category
            <input type="text" style="width: 600px">
          </div>
          <div class="topnavbar">
              <ul>
                  <li>Become an Instructor</li>
                  <li>For Enterprise</li>
                  <li>Log in</li>
                  <li><a href=""></a></li>
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
          margin-right: 5%;
          margin-left: 5%;
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