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
</style>