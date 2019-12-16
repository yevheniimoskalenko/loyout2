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
          We are working with both individuals and businesses from all over the
          globe
          <br />to create awesome websites and applications.
        </p>
        <div class="row">
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/flag.png" alt class="services__img" />
              <h3>Branding</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                diam nonummy nibh.
              </p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/pain.png" alt class="services__img" />
              <h3>Design</h3>
              <p>
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              </p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/settings.png" alt class="services__img" />
              <h3>Development</h3>
              <p>
                At vero eos et accusamus et iusto odio dignissimos qui
                blanditiis praesentium.
              </p>
            </div>
          </div>
          <div class="col">
            <div class="services__iteam">
              <img src="../assets/rocket.png" alt class="services__img" />
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
              <div class="col">
                <div class="team__iteam">
                  <img src="../assets/Base.png" alt class="team__img" />
                  <div class="team__name">Anne hathaway</div>
                  <div class="team__work">CEO / Marketing Guru</div>
                  <p class="team__info">
                    Lorem ipsum dolor sit amet, consectetuer adipiscing elit,
                    sed diam nonummy nibh euismod tincidunt ut laoreet dolore
                    magna.
                  </p>
                  <div class="social">
                    <div class="row d-flex justify-content-center">
                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Facebook_Icon.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Twitter.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Mail.png" alt />
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="team__iteam">
                  <img src="../assets/Base.png" alt class="team__img" />
                  <div class="team__name">Kate Upton</div>
                  <div class="team__work">Creative Director</div>
                  <p class="team__info">
                    Duis aute irure dolor in in voluptate velit esse cillum
                    dolore fugiat nulla pariatur. Excepteur sint occaecat non
                    diam proident.
                  </p>

                  <div class="social">
                    <div class="row d-flex justify-content-center">
                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Facebook_Icon.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Twitter.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Mail.png" alt />
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="team__iteam">
                  <img src="../assets/Base.png" alt class="team__img" />
                  <div class="team__name">Olivia Wilde</div>
                  <div class="team__work">Lead Designer</div>
                  <p class="team__info">
                    Nemo enim ipsam voluptas sit aspernatur aut odit aut fugit,
                    sed quia consequuntur magni dolores eos qui ratione
                    voluptatem nesciunt.
                  </p>
                  <div class="social">
                    <div class="row d-flex justify-content-center">
                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Facebook_Icon.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Twitter.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Mail.png" alt />
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="team__iteam">
                  <img src="../assets/Base.png" alt class="team__img" />
                  <div class="team__name">Ashley Greene</div>
                  <div class="team__work">SEO / Developer</div>
                  <p class="team__info">
                    Sed ut perspiciatis unde omnis iste natus error sit
                    voluptatem accusantium doloremque laudantium, totam rem
                    aperiam.
                  </p>
                  <div class="social">
                    <div class="row d-flex justify-content-center">
                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Facebook_Icon.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Twitter.png" alt />
                        </div>
                      </div>

                      <div class="col">
                        <div class="social__iteam">
                          <img src="../assets/Mail.png" alt />
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="skills">
      <div class="container">
        <div class="skill__contant">
          <h2>WE GOT SKILLS!</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod <br />
            tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
        <div class="progress_skills">
          <div class="row">
            <div class="col">
              <div class="progress__iteam">
                <Progress
                  strokeColor="#30bae7"
                  :transitionDuration="2000"
                  :radius="50"
                  :strokeWidth="10"
                  value="90"
                >
                  <template v-slot:footer>
                    <div class="progress__footer">
                      <b>Web Design</b>
                    </div>
                  </template>
                </Progress>
              </div>
            </div>
            <div class="col">
              <div class="progress__iteam">
                <Progress
                  strokeColor="#d74680"
                  :transitionDuration="2000"
                  :radius="50"
                  :strokeWidth="10"
                  value="75"
                >
                  <template v-slot:footer>
                    <div class="progress__footer">
                      <b>HTML / CSS</b>
                    </div>
                  </template>
                </Progress>
              </div>
            </div>
            <div class="col">
              <div class="progress__iteam">
                <Progress
                  strokeColor="#15c7a8"
                  :transitionDuration="2000"
                  :radius="50"
                  :strokeWidth="10"
                  value="70"
                >
                  <template v-slot:footer>
                    <div class="progress__footer">
                      <b>GRAPHIC DESIGN</b>
                    </div>
                  </template>
                </Progress>
              </div>
            </div>
            <div class="col">
              <div class="progress__iteam">
                <Progress
                  strokeColor="#eb7d4b"
                  :transitionDuration="2000"
                  :radius="50"
                  :strokeWidth="10"
                  value="85"
                >
                  <template v-slot:footer>
                    <div class="progress__footer">
                      <b>UI / UX</b>
                    </div>
                  </template>
                </Progress>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import Progress from "easy-circular-progress/src/index";
export default {
  components: { Progress }
};
</script>
<style lang="scss" scoped>
.team {
  width: 100%;
  height: 940px;
  background-color: #e7f1f8;
}
.beautiful_team {
  padding: 120px 0px;
  h2 {
    color: #3c4761;
    font-size: 41px;
    font-weight: 700;
    text-transform: uppercase;
    line-height: 30.87px;
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
    padding-bottom: 50px;
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
.social__iteam {
  background-color: #bdd1df;
  width: 32px;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
}
.team__iteam {
  padding: 0px 20px;
}
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
.skills {
  width: 100%;
  height: 650px;
  background-color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
}
.skill__contant {
  h2 {
    font-size: 40px;
    color: #3c4761;
    font-weight: 700;
    text-transform: uppercase;
    text-align: center;
  }
  p {
    color: #3c4761;
    font-size: 18px;
    font-weight: 400;
    line-height: 30px;
    letter-spacing: 0.36px;
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
}
.progress_skills {
  margin-top: 80px;
}
.progress__iteam {
  display: flex;
  justify-content: center;
}
.progress__footer {
  padding-top: 30px;
  text-align: center;
  b {
    font-size: 18px;
    font-weight: 700;
  }
}
</style>
