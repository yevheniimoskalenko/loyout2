<template>
  <section class="people">
    <div class="container">
      <div class="people__content">
        <h2>WHAT POEPLE SAY ABOUT US</h2>
        <p>Our clients love us!</p>
      </div>
      <div class="people__comment">
        <div class="row">
          <div class="col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6">
            <div class="comment">
              <div class="row">
                <div class="col-3">
                  <img src="../assets/Base.png" alt class="avatar" />
                </div>
                <div class="col">
                  <div class="comment__content">
                    <p>“Nullam dapibus blandit orci, viverra gravida dui lobortis eget. Maecenas fringilla urna eu nisl scelerisque.”</p>
                    <div class="names__people">Chanel Iman</div>
                    <div class="work__people">CEO of Pinterest</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6">
            <div class="comment">
              <div class="row">
                <div class="col-3">
                  <img src="../assets/Base.png" alt class="avatar" />
                </div>
                <div class="col">
                  <div class="comment__content">
                    <p>“Nullam dapibus blandit orci, viverra gravida dui lobortis eget. Maecenas fringilla urna eu nisl scelerisque.”</p>
                    <div class="names__people">Chanel Iman</div>
                    <div class="work__people">CEO of Pinterest</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6">
            <div class="comment">
              <div class="row">
                <div class="col-3">
                  <img src="../assets/Base.png" alt class="avatar" />
                </div>
                <div class="col">
                  <div class="comment__content">
                    <p>“Nullam dapibus blandit orci, viverra gravida dui lobortis eget. Maecenas fringilla urna eu nisl scelerisque.”</p>
                    <div class="names__people">Chanel Iman</div>
                    <div class="work__people">CEO of Pinterest</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6">
            <div class="comment">
              <div class="row">
                <div class="col-3">
                  <img src="../assets/Base.png" alt class="avatar" />
                </div>
                <div class="col">
                  <div class="comment__content">
                    <p>“Nullam dapibus blandit orci, viverra gravida dui lobortis eget. Maecenas fringilla urna eu nisl scelerisque.”</p>
                    <div class="names__people">Chanel Iman</div>
                    <div class="work__people">CEO of Pinterest</div>
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
// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (max-width: 576px) {
  .comment {
    img {
      width: 50px;
      height: 50px;
    }
  }
}
@media (min-width: 576px) {
  .comment__content {
    p {
      font-size: 12px;
      margin-left: 20px;
    }
    .names__people {
      margin-left: 20px;
    }
    .work__people {
      margin-left: 20px;
    }
  }
  .comment {
    img {
      width: 60px;
      height: 60px;
    }
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .comment__content {
    p {
      font-size: 14px;
      margin-left: 20px;
    }
    .names__people {
      margin-left: 20px;
    }
    .work__people {
      margin-left: 20px;
    }
  }
  .comment {
    img {
      width: 72px;
      height: 72px;
    }
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .comment__content {
    p {
      font-size: 14px;
    }
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .comment__content {
    p {
      font-size: 14px;
    }
  }
}
.mt {
  margin-top: 140px;
}
.names__people {
  font-size: 24px;
  font-weight: 700;
  line-height: 26px;
  text-transform: uppercase;
}
.work__people {
  font-size: 18px;
  line-height: 26px;
  color: #ffdd99;
}
.comment {
  img {
    background-size: cover;
    display: block;
  }
}
.comment__content p {
  font-style: italic;
  line-height: 31px;
  text-align: left;
}

.people {
  background-color: #d74680;
  width: 100%;
  // height: 900px;
  padding: 120px 0;
  display: flex;
  justify-content: center;
}
.people {
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  h2 {
    text-align: center;
    font-size: 40px;
    font-weight: 700;
    line-height: 40px;
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
    font-weight: 400;
  }
}
.people__content {
  text-align: center;
  font-size: 24px;
  margin-bottom: 40px;
}
.people__comment {
  margin-top: 40px;
}
</style>