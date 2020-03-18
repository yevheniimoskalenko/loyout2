<template>
  <div class="header">
    <div class="container">
      <div class="menu">
        <div class="row">
          <div class="col">
            <nav class="navbar navbar-expand-lg navbar-light">
              <img src="../assets/logo.png" class="logo navbar-brand" />
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                  <router-link to="/" class="nav-item nav-link active">home</router-link>
                  <router-link to="/" class="nav-item nav-link">about</router-link>
                  <router-link to="/" class="nav-item nav-link">work</router-link>
                  <router-link to="/" class="nav-item nav-link">blog</router-link>
                  <router-link to="/" class="nav-item nav-link">contact</router-link>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
      <div class="row header__title d-flex flex-column align-items-center">
        <div class="col">
          <h1 class="text-center">
            Hi there! We are the new kids on the block
            <br />and we build awesome websites and mobile apps.
          </h1>
        </div>
        <div class="col d-flex justify-content-center">
          <button class="work">work with us!</button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import $ from "jquery";
export default {
  ready() {
    $(document).ready(function($) {
      $("#navbarNavAltMarkup").collapse({
        toggle: false
      });
    });
  }
};
</script>
<style lang="scss" scoped>
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (min-width: 576px) {
  .header__title {
    padding: 80px 0px 0px 0px;
  }
  .header__title h1 {
    font-size: 26px;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .header__title h1 {
    font-size: 36px;
  }
  // .header__title {
  //   padding: 150px 0px 0px 0px;
  // }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .header__title h1 {
    font-size: 36px;
  }
  // .header__title {
  //   padding: 150px 0px 0px 0px;
  // }
}

// // Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .header__title h1 {
    color: #f7f3ea;
    font-family: "Titillium Web";
    font-size: 42px;
    font-weight: 700;
    line-height: 48.82px;
  }
  // .header__title {
  //   padding: 150px 0px 0px 0px;
  // }
}
.header__title h1 {
  color: #f7f3ea;
  font-family: "Titillium Web";
  font-weight: 700;
  line-height: 48.82px;
}
// .header__title {
//   text-align: center;
// }
.header__title h1 {
}
.logo {
  width: 100px;
}
.menu {
  padding-top: 60px;
}
.header {
  background-color: #87509c;
  height: 596px;
}

.nav-item {
  margin: 0px 10px;
}
.navbar-nav a {
  color: #fff;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 16px;
  font-weight: 400;
  line-height: 18px;
  padding: 5px 6px;
  border-radius: 3px;
}
.active {
  background-color: #643a79;
  color: #fff;
}
.navbar-nav a:hover {
  background-color: #643a79;
  color: #fff;
}
.work {
  margin-top: 60px;
  background-color: #eb7d4b;
  border: none;
  color: #fff;
  padding: 20px 80px;
  text-transform: uppercase;
  border-bottom: 2px solid rgba(0, 0, 0, 0.308);
  border-radius: 3px;
}
</style>