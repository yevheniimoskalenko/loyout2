<template>
  <div class="container-fluid">
    <app-Header />
    <app-Services />
    <app-Team />
    <app-Skills />
    <app-Portfolio />
    <app-People />
    <app-Tuch />
    <app-Footer />
  </div>
</template>
<script>
import appHeader from "../components/header";
import appServices from "../components/services";
import appTeam from "../components/team";
import appSkills from "../components/skills";
import appPortfolio from "../components/portfolio";
import appPeople from "../components/people";
import appTuch from "../components/get_tuch";
import appFooter from "../components/footer";

export default {
  components: {
    appHeader,
    appServices,
    appTeam,
    appSkills,
    appPortfolio,
    appPeople,
    appTuch,
    appFooter
  }
};
</script>
<style lang="scss" scoped>
.container-fluid {
  padding-left: 0px;
  padding-right: 0px;
}
</style>
