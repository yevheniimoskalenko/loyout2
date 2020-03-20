<template>
  <section class="services">
    <div class="container">
      <h2>services we provede</h2>
      <p>
        We are working with both individuals and businesses from all over the
        globe
        <br />to create awesome websites and applications.
      </p>
      <div class="row">
        <div class="col-6 col-md-6 col-lg">
          <div class="services__iteam">
            <div class="services__block">
              <img src="../assets/flag.png" alt class="services__img" />
            </div>
            <h3>Branding</h3>
            <p>
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
              diam nonummy nibh.
            </p>
          </div>
        </div>
        <div class="col-6 col-md-6 col-lg">
          <div class="services__iteam">
            <div class="services__block">
              <img src="../assets/pain.png" alt class="services__img" />
            </div>
            <h3>Design</h3>
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem</p>
          </div>
        </div>
        <div class="col-6 col-md-6 col-lg">
          <div class="services__iteam">
            <div class="services__block">
              <img src="../assets/settings.png" alt class="services__img" />
            </div>
            <h3>Development</h3>
            <p>
              At vero eos et accusamus et iusto odio dignissimos qui
              blanditiis praesentium.
            </p>
          </div>
        </div>
        <div class="w100 d-lg-none .d-xl-block"></div>
        <div class="col-6 col-md-6 col-lg">
          <div class="services__iteam">
            <div class="services__block">
              <img src="../assets/rocket.png" alt class="services__img" />
            </div>
            <h3>roket science</h3>
            <p>
              Et harum quidem rerum est et expedita distinctio. Nam libero
              tempore.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (min-width: 576px) {
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .services__block {
    width: 100%;
    height: 100px;
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
}
.services {
  // height: 747px;
  background-color: #17c2a4;
}
.services__img {
  background-size: cover;
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
</style>