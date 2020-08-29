<template>
  <section class="get__tuach">
    <div class="container">
      <div class="touch">
        <h2>GET IN TOUCH</h2>
        <p>1600 Pennsylvania Ave NW, Washington, DC 20500, United States of America. Tel: (202) 456-1111</p>
        <div class="touch__form">
          <form>
            <div class="row">
              <div class="col">
                <div class="form_group">
                  <input type="text" class="form-control bgc" placeholder="Your Name *" />
                </div>
              </div>
              <div class="col">
                <div class="form_group">
                  <input type="text" class="form-control bgc" placeholder="Your Name *" />
                </div>
              </div>
            </div>
            <div class="form_group">
              <textarea class="form-control textr bgc" placeholder="Your Name *"></textarea>
            </div>
            <div class="d-flex justify-content-center">
              <button class="send_message">SEND MESSAGE</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.get__tuach {
  width: 100%;
  height: 800px;
  background-color: #3c5499;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
}
.touch {
  h2 {
    text-align: center;
    font-size: 40px;
    font-weight: 700;
    line-height: 29.91px;
    text-transform: uppercase;
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
    text-align: center;
    font-size: 18px;
    font-weight: 400;
  }
}
.touch__form {
  margin-top: 75px;
}
.bgc {
  background-color: #273a71;
  border: none;
  color: #fff;
  padding: 20px 15px;
}
.textr {
  margin-top: 20px;
  height: 200px;
}
.send_message {
  margin-top: 60px;
  background-color: #30bae7;
  border: none;
  color: #fff;
  padding: 20px 80px;
  text-transform: uppercase;
  border-bottom: 2px solid rgba(0, 0, 0, 0.308);
  border-radius: 3px;
}
// Small devices (landscape phones, 576px and up)
@media (max-width: 576px) {
}
@media (min-width: 576px) {
}
// Medium devices (tablets, 768px and up)
@media (min-width: 768px) {
}

// Large devices (desktops, 992px and up)
@media (min-width: 992px) {
}

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) {
}
</style>