<template>
  <section class="team">
    <div class="container">
      <div class="beautiful_team">
        <h2>MEET OUR BEAUTIFUL TEAM</h2>
        <p>
          We are a small team of designers and developers, who help brands
          with big ideas.
        </p>
        <div class="team_all">
          <div class="row">
            <div class="col-12 col-xs-6 col-sm-6 col-sm-6 col-md-6 col-lg-6 col-xl-6">
              <div class="team__iteam">
                <img src="../assets/pngfuel.com.png" alt class="team__img" />
                <div class="team__name">Anne hathaway</div>
                <div class="team__work">CEO / Marketing Guru</div>
                <div class="team__content">
                  <p class="team__info">
                    Lorem ipsum dolor sit amet, consectetuer adipiscing elit,
                    sed diam nonummy nibh euismod tincidunt ut laoreet dolore
                    magna.
                  </p>
                </div>
                <div class="social">
                  <div class="social__iteam">
                    <a href="#facebook">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </div>

                  <div class="social__iteam">
                    <a href="#twitter">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </div>

                  <div class="social__iteam">
                    <a href="#instagram">
                      <i class="fab fa-instagram"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-12 col-xs-6 col-sm-6 col-sm-6 col-md-6 col-lg-6 col-xl-6">
              <div class="team__iteam">
                <img src="../assets/pngfuel.com.png" alt class="team__img" />
                <div class="team__name">Kate Upton</div>
                <div class="team__work">Creative Director</div>
                <div class="team__content">
                  <p class="team__info">
                    Duis aute irure dolor in in voluptate velit esse cillum
                    dolore fugiat nulla pariatur. Excepteur sint occaecat non
                    diam proident.
                  </p>
                </div>
                <div class="social">
                  <div class="social__iteam">
                    <a href="#facebook">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </div>

                  <div class="social__iteam">
                    <a href="#twitter">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </div>
                  <div class="social__iteam">
                    <a href="#instagram">
                      <i class="fab fa-instagram"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-12 col-xs-6 col-sm-6 col-sm-6 col-md-6 col-lg-6 col-xl-6">
              <div class="team__iteam team__iteam-footer">
                <img src="../assets/pngfuel.com.png" alt class="team__img" />
                <div class="team__name">Olivia Wilde</div>
                <div class="team__work">Lead Designer</div>
                <div class="team__content">
                  <p class="team__info">
                    Nemo enim ipsam voluptas sit aspernatur aut odit aut fugit,
                    sed quia consequuntur magni dolores eos qui ratione
                    voluptatem nesciunt.
                  </p>
                </div>
                <div class="social">
                  <div class="row d-flex justify-content-center">
                    <div class="social__iteam">
                      <a href="#facebook">
                        <i class="fab fa-facebook-f"></i>
                      </a>
                    </div>
                  </div>
                  <div class="social__iteam">
                    <a href="#twitter">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </div>
                  <div class="social__iteam">
                    <a href="#instagram">
                      <i class="fab fa-instagram"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-12 col-xs-6 col-sm-6 col-sm-6 col-md-6 col-lg-6 col-xl-6">
              <div class="team__iteam team__iteam-footer d-flex flex-column">
                <img src="../assets/pngfuel.com.png" alt class="team__img" />
                <div class="team__name">Ashley Greene</div>
                <div class="team__work">SEO / Developer</div>
                <div class="team__content">
                  <p class="team__info">
                    Sed ut perspiciatis unde omnis iste natus error sit
                    voluptatem accusantium doloremque laudantium, totam rem
                    aperiam.
                  </p>
                </div>
                <div class="social">
                  <div class="social__iteam">
                    <a href="#facebook">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </div>
                  <div class="social__iteam">
                    <a href="#twitter">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </div>
                  <div class="social__iteam">
                    <a href="#instagram">
                      <i class="fab fa-instagram"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
@media (max-width: 576px) {
  .team__iteam {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 0px;
  }
  .beautiful_team {
    p {
      padding-bottom: 0px;
    }
  }
  .team__img {
    width: 60%;
  }
  .team__iteam-footer {
    margin-top: 0px;
  }
  .team__content {
    height: 100px;
  }
  .team__content {
    height: 150px;
  }
}
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (min-width: 576px) {
  .beautiful_team {
    p {
      padding-bottom: 0px;
    }
  }
  .team__iteam img {
    width: 100%;
  }
  .team__iteam-footer {
    margin-top: 0px;
  }
  .team__content {
    height: 100px;
  }
  .team__content {
    height: 150px;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .beautiful_team {
    p {
      padding-bottom: 50px;
    }
  }
  .team__iteam img {
    width: 100%;
  }
  .team__iteam-footer {
    margin-top: 0px;
  }
  .team__content {
    height: 100px;
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .beautiful_team {
    p {
      padding-bottom: 50px;
    }
  }
  .team__iteam img {
    width: 50%;
    margin: auto;
  }
  .team__iteam-footer {
    margin-top: 40px;
  }
  .team__content {
    height: 100px;
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .beautiful_team {
    p {
      padding-bottom: 50px;
    }
  }
  .team__iteam img {
    width: 80%;
  }
  .team__iteam-footer {
    margin-top: 0px;
  }
  .team__content {
    height: 150px;
  }
}
.team {
  width: 100%;

  background-color: #e7f1f8;
}
.fab {
  color: #fff;
}
.team__content {
  display: block;
  overflow: hidden;
}
.beautiful_team {
  padding: 120px 0px;
  h2 {
    color: #3c4761;
    font-size: 41px;
    font-weight: 700;
    text-transform: uppercase;
    line-height: 50px;
    letter-spacing: 4px;
    text-align: center;
  }
  h2::after {
    content: "";
    display: block;
    margin: 20px auto;
    width: 87px;
    height: 4px;
    background: rgba(0, 0, 0, 0.155);
  }
  p {
    font-size: 19px;
    line-height: 26.84px;
    font-weight: 400;
    text-align: center;
    color: #3c4761;
  }
  .team__img {
    padding-bottom: 40px;
  }
  .team__name {
    text-transform: uppercase;
    color: #27283d;
    font-size: 24px;
    line-height: 18px;
    font-weight: 700;
    text-align: center;
    padding-bottom: 15px;
  }
  .team__work {
    color: #30bae7;
    font-size: 16px;
    font-weight: 400;
    line-height: 18px;
    text-align: center;
    padding-bottom: 30px;
    margin: auto;
  }
  .team__info {
    color: #3c4761;
    font-size: 16px;
    line-height: 24px;
    font-weight: 300;
    padding: 0px 0px 15px;
  }
}
.social {
  display: flex;
  justify-content: center;
  flex-direction: row;
  align-items: center;
}
.social__iteam {
  background-color: #bdd1df;
  width: 32px;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  margin: auto 10px;
}
.team__iteam {
  padding: 0px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  img {
    background-size: cover;

    border-radius: 50%;
  }
}
</style>