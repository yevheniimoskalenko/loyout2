<template>
  <section class="skills">
    <div class="container">
      <div class="skill__contant">
        <div class="title">
          <h2>WE GOT SKILLS!</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod
            <br />tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>
      <div class="progress_skills">
        <div class="row">
          <div class="col-6 col-sm-6 col-md-6 col-lg-6 col-xl">
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
          <div class="col-6 col-sm-6 col-md-6 col-lg-6 col-xl">
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
          <div class="col-6 col-sm-6 col-md-6 col-lg-6 col-xl">
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
          <div class="col-6 col-sm-6 col-md-6 col-lg-6 col-xl">
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
</template>
<script>
import Progress from "easy-circular-progress/src/index";
export default {
  components: { Progress },
};
</script>
<style lang="scss" scoped>
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (max-width: 576px) {
  .skills {
    padding: 120px 0;
  }
}
@media (min-width: 576px) {
  .skills {
    padding: 120px 0;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .skills {
    padding: 120px 0;
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .skills {
    padding: 120px 0;
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .skills {
    height: 600px;
  }
}
.skills {
  width: 100%;

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
    line-height: 50px;
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
    padding-bottom: 20px;
    display: block;
  }
}
</style>