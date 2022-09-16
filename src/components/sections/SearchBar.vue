<template>
  <div class="container">
    <div class="topbar">
      <div class="lang" style="align-self: center;">
        <img src="../../assets/img/MasterStudy.svg" alt="" style="height: 45px;">
      </div>
      <div class="MiddleSearch">
        <span style="margin-right: 20px; color: gray;">CATEGORY</span>
        <input type="text" class="SearchBar" placeholder="Search Courses">
        <button class="SearchButton"></button>
      </div>
      <div class="RightSearch">
        <ul>
          <li>Become an Instructor</li>
          <li><span style="margin-right: 80px;">For Enterprise</span></li>
          <li>Log in</li>
          <li><a href="">SIGN UP</a></li>
          <li><img src="../../assets/img/icons/iconmonstr-heart-thin.svg" alt=""></li>
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
      margin: auto;
      display: inline;

      li {
        display: inline;
        margin-right: 20px;
        color: darkblue;
        font-size: 16px;

        a {
          border-radius: 35px;
          background: #ff4450;
          padding: 15px 30px 15px 30px;
          width: 450px;
          height: 150px;
          text-decoration: none;
          color: white;
          font-size: 18px;

        }

        a:hover {
          background: #375ca2;
          transition: 0.2s;
        }
      }
    }
  }

  .arrow {
    height: 12px;
    margin-left: 5px;
  }

  .MiddleSearch {
    display: flex;
    align-items: center;
  }

  .SearchBar {
    width: 500px;
    height: 45px;
  }

  .SearchButton {
    width: 60px;
    height: 50px;
  }
}
</style>