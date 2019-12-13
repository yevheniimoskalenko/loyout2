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
            <br />and we build awesome websites and mobile apps.
          </h1>

          <button class="work">work with us!</button>
        </div>
      </div>
    </div>
    <section class="services">
      <div class="container">
        <h2>services we provede</h2>
        <p>
          We are working with both individuals and businesses from all over the globe
          <br />to create awesome websites and applications.
        </p>
        <div class="row">
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/flag.png" alt class="services__img" />
              <h3>Branding</h3>
              <p>
                Lorem ipsum dolor sit amet,
                consectetuer adipiscing elit, sed diam nonummy nibh.
              </p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/pain.png" alt class="services__img" />
              <h3>Design</h3>
              <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem</p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/settings.png" alt class="services__img" />
              <h3>Development</h3>
              <p>At vero eos et accusamus et iusto odio dignissimos qui blanditiis praesentium.</p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/rocket.png" alt class="services__img" />
              <h3>roket science</h3>
              <p>Et harum quidem rerum est et expedita distinctio. Nam libero tempore.</p>
            </div>
          </div>
        </div>
      </div>
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
.services {
  color: #fff;
  padding: 120px 0px;
}
.services h2 {
  font-size: 40px;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  padding-bottom: 25px;
}
.services h2::after {
  content: "";
  display: block;
  margin: 15px auto;
  width: 87px;
  height: 4px;
  background: rgba(0, 0, 0, 0.155);
}
.services__img {
  display: block;
  margin: auto;
}
.services p {
  text-align: center;
  font-size: 18px;
  padding-bottom: 80px;
}

.services__iteam h3,
.services__iteam p {
  text-align: center;
}
.services__iteam h3 {
  font-weight: 700;
  font-size: 24px;
  line-height: 18px;
  text-transform: uppercase;
  padding-top: 60px;
}
.services__iteam {
  padding: 0px 15px;
}
.services__iteam p {
  line-height: 24px;
  font-weight: 300;
  letter-spacing: 0.32px;
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
.services {
  // height: 747px;
  background-color: #17c2a4;
}
</style>