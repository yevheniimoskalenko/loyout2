<template>
  <section class="footer d-flex justify-content-center align-items-center">
    <div class="container">
      <div class="footer__link">
        <router-link to="/">Facebook</router-link>
        <router-link to="/">Twitter</router-link>
        <router-link to="/">Linkedln</router-link>
        <router-link to="/">GitHab</router-link>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 112px;
  background: #344b8e;
}
.footer__link {
  display: flex;
  justify-content: center;
  align-items: center;
  a {
    font-size: 24px;
    font-weight: 400;
    color: #ffffff;
    line-height: 29.91px;
    text-decoration: none;
    padding: 0px 25px;
  }
  a:hover {
    color: #30bae7;
  }
}
// Small devices (landscape phones, 576px and up)
@media (max-width: 576px) {
  .footer__link {
    a {
      font-size: 16px;
      padding: 0px 14px;
    }
  }
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