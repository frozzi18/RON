<template>
  <div id="app">
   <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,500');

@import url('https://indestructibletype-fonthosting.github.io/jost.css');

#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.headline-biggest {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 72px;
  letter-spacing: .24px;
  line-height: 90px;
}

.headline-big {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 56px;
  letter-spacing: .24px;
  line-height: 76px;
}

.headline-medium {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 40px;
  letter-spacing: .24px;
  line-height: 60px;
}

.headline-normal {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 28px;
  letter-spacing: .08px;
  line-height: 38px;
}

/*Second-not*/

.headline-small {
  font-family: 'Montserrat';
  font-weight:500;
  font-size: 20px;
  letter-spacing: .16px;
  line-height: 30px;
}

.headline-smallest {
  font-family: 'Montserrat';
  font-weight:500;
  font-size: 16px;
  letter-spacing: .16px;
  line-height: 24px;
}

.subheadline-1 {
  font-family: 'Jost*';
  font-weight:400;
  font-size: 24px;
  letter-spacing: .16px;
  line-height: 34px;
}

.subheadline-2 {
  font-family: 'Jost*';
  font-weight:400;
  font-size: 16px;
  letter-spacing: .2px;
  line-height: 26px;
}

.menu {
  font-family: 'Jost*';
  font-weight:400;
  font-size: 12px;
  letter-spacing: 1px;
  line-height: 20px;
}

/*Third*/

.submenu {
  font-family: 'Jost*';
  font-weight:400;
  font-size: 16px;
  letter-spacing: .2px;
  line-height: 26px;
}

.body-18px {
  font-family: 'Jost*';
  font-weight:300;
  font-size: 18px;
  letter-spacing: .2px;
  line-height: 28px;
}

.body-2-18px {
  font-family: 'Montserrat';
  font-weight:500;
  font-size: 16px;
  letter-spacing: .2px;
  line-height: 26px;
}

.button {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 14px;
  letter-spacing: .4px;
  line-height: 14px;
}

.caption {
  font-family: 'Jost*';
  font-weight:300;
  font-size: 13px;
  letter-spacing: .32px;
  line-height: 23px;
}

/*Fourth*/
.body-16px {
  font-family: 'Jost*';
  font-weight:300;
  font-size: 16px;
  letter-spacing: .2px;
  line-height: 26px;
}

.body-2-16px {
  font-family: 'Montserrat';
  font-weight:500;
  font-size: 16px;
  letter-spacing:.2px;
  line-height: 26px;
}

.overline {
  font-family: 'Montserrat';
  font-weight:500;
  font-size: 12px;
  letter-spacing: 1px;
  line-height: 20px;
}
</style>
