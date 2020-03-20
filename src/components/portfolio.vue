<template>
  <section class="portfolio">
    <div class="container">
      <div class="container__portfolio">
        <h2>OUR PORTFOLIO</h2>
        <p>
          Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet
          <br />consectetur, adipisci velit, sed quia non numquam
        </p>
        <div class="link__portfolio">
          <div class="row">
            <div class="col">
              <button class="btn btn-light actived">all</button>
            </div>
            <div class="col">
              <button class="btn btn-light">web</button>
            </div>
            <div class="col">
              <button class="btn btn-light">apps</button>
            </div>
            <div class="col">
              <button class="btn btn-light">icons</button>
            </div>
          </div>
        </div>
        <div class="project__portfolio">
          <div class="row">
            <div class="col-6">
              <div class="project__item">
                <img src="../assets/1.png" alt />
                <p>Isometric Perspective Mock-Up</p>
              </div>
            </div>
            <div class="col-6">
              <div class="project__item">
                <img src="../assets/2.png" alt />
                <p>Time Zone App UI</p>
              </div>
            </div>
            <div class="col-6">
              <div class="project__item">
                <img src="../assets/3.png" alt />
                <p>Viro Media Players UI</p>
              </div>
            </div>
            <div class="col-6">
              <div class="project__item">
                <img src="../assets/4.png" alt />
                <p>Blog / Magazine Flat UI Kit</p>
              </div>
            </div>
          </div>
        </div>
        <div class="load__project">
          <button class="more">LOAD MORE PROJECTS</button>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
@media (max-width: 576px) {
  .project__item img {
    width: 90%;
    background-size: cover;
  }
  .portfolio {
    height: 1050px;
  }
}
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (min-width: 576px) {
  .project__item img {
    width: 90%;
    background-size: cover;
  }
  .portfolio {
    height: 1050px;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .project__item img {
    width: 100%;
    background-size: cover;
  }
  .portfolio {
    height: 1400px;
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .project__item img {
    width: 100%;
    background-size: cover;
  }
  .portfolio {
    height: 1400px;
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .project__item img {
    width: 100%;
    background-size: cover;
  }
  .portfolio {
    height: 1400px;
  }
}
.actived {
  background-color: #fff;
  color: #000;
}
.portfolio {
  width: 100%;
  background-color: #ffdd99;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #393939;

  h2::after {
    content: "";
    display: block;
    margin: 20px auto;
    width: 87px;
    height: 4px;
    background: rgba(0, 0, 0, 0.155);
  }
  h2 {
    text-align: center;
    font-size: 40px;
    font-weight: 700;
    line-height: 29.91px;
    text-transform: uppercase;
  }
  p {
    text-align: center;
    font-size: 18px;
    font-weight: 400;
  }
  .link__portfolio {
    display: flex;
    justify-content: center;
  }
}
.btn-light {
  font-size: 18px;
  text-transform: uppercase;
  font-weight: 400;
  line-height: 19.5px;
  background-color: rgba(0, 0, 0, 0.155);
  border: none;
  &:hover {
    background-color: #fff;
    color: #000;
  }
}
.project__portfolio {
  margin: 60px 0px 0px 0px;
  p {
    font-size: 18px;
    font-weight: 400;
    line-height: 19px;
    text-transform: uppercase;
    letter-spacing: 0.36px;
    text-align: center;
    margin: 30px;
  }
}

.more {
  margin-top: 60px;
  background-color: #17c2a4;
  border: none;
  color: #fff;
  padding: 20px 80px;
  text-transform: uppercase;
  border-bottom: 2px solid rgba(0, 0, 0, 0.308);
  border-radius: 3px;
}

.load__project {
  display: flex;
  justify-content: center;
}
</style>