<template>
  <HeaderComponent />
  <HeroComponent />
  <SkillsComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent'
import HeroComponent from './components/HeroComponent'
import SkillsComponent from './components/SkillsComponent'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    HeroComponent,
    SkillsComponent
  }
}
</script>

<style lang="scss">

body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background: #171718;
  color: #FFFFFF;
}

h1 {
  font-family: 'DM Sans', sans-serif;
  font-weight: 700;
  font-size: 34px;
  line-height: 40px;
  letter-spacing: 0.25px;
  @media only screen and (min-width: 1200px) {
    font-size: 60px;
    line-height: 71px;
    letter-spacing: -0.5px;
  }
}

h2 {
  font-family: 'DM Sans', sans-serif;
  font-weight: 400;
  font-size: 24px;
  line-height: 32px;
  letter-spacing: 0.25px;
  @media only screen and (min-width: 1200px) {
    font-weight: 500;
    font-size: 34px;
    line-height: 40px;
  }
}

p {
  font-family: 'DM Sans', sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 28px;
  letter-spacing: 0.44px;
  color: #FFFFFF;

}

.container {
  max-width: 1156px;
  padding: 0 16px;
  margin: 0 auto;
  @media only screen and (min-width: 1200px) {
    padding: 0;

  }
}

</style>
