<template>
  <div class="container-fluid">
    <div class="header">
      <div class="container">
        <div class="menu">
          <div class="row">
            <div class="col">
              <img src="../assets/logo.png" class="logo" />
            </div>
            <div class="col">
              <ul class="menu__link">
                <li>
                  <router-link to="/" class="menu__active">home</router-link>
                </li>
                <li>
                  <router-link to="/">about</router-link>
                </li>
                <li>
                  <router-link to="/">work</router-link>
                </li>
                <li>
                  <router-link to="/">blog</router-link>
                </li>

                <li>
                  <router-link to="/">contact</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="header__title">
          <h1>
            Hi there! We are the new kids on the block
            and we build awesome websites and mobile apps.
          </h1>

          <button class="work">work with us!</button>
        </div>
      </div>
    </div>
    <section class="services">
      <h2>services we provede</h2>
    </section>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.header__title h1 {
  color: #f7f3ea;
  font-family: "Titillium Web";
  font-size: 42px;
  font-weight: 700;
  line-height: 48.82px;
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
.header {
  background-color: #87509c;
  height: 596px;
}
.header__title {
  padding: 150px 0px 0px 0px;
  text-align: center;
}
.menu__link li {
  list-style-type: none;
  float: left;
  padding: 0px 20px;
}
.menu__link a {
  color: #fff;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 16px;
  font-weight: 400;
  line-height: 18px;
  padding: 5px 6px;
  border-radius: 3px;
}
.menu__active {
  background-color: #643a79;
}
.menu__link a:hover {
  background-color: #643a79;
}
.container-fluid {
  padding-left: 0px;
  padding-right: 0px;
}
.logo {
  width: 100px;
}
.menu {
  padding-top: 60px;
}
</style>