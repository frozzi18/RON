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
  color: #000000;
  margin-top: 60px;
  opacity: 100%;
}

.headline-biggest {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 72px;
  letter-spacing: .24px;
  line-height: 90px;
}

.headline-medium-title {
  font-family: 'Montserrat';
  font-weight:400;
  font-size: 20px;
  letter-spacing: .16px;
  line-height: 28px;
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

.no-underline {
  text-decoration: none;
}

.margin-top-navbar{
  padding-top: 25px;
}

.height-navbar {
  height: 80px;
}

.cool-link {
    display: inline-block;
    color: black;
    text-decoration: none;

}

.cool-link::after {
    content: '';
    display: block;
    width: 0;
    height: 2px;
    background: black;
    margin-top: 18px;
    transition: width .3s;
}

.cool-link:hover::after {
    width: 100%;
    //transition: width .3s;
}

.cool-link-2 {
    display: inline-block;
    color: white;
    text-decoration: none;

}

.cool-link-2::after {
    content: '';
    display: block;
    width: 0;
    height: 2px;
    background: white;
    margin-top: 18px;
    transition: width .3s;
}

.cool-link-2:hover::after {
    width: 100%;
    //transition: width .3s;
}

.active {
    display: inline-block;
    color: black;
    text-decoration: none;

}

.active::after {
    content: '';
    display: block;
    /*width: 0;*/
    height: 2px;
    background: black;
    margin-top: 18px;
    transition: width .3s;
}

.active:hover::after {
    width: 100%;
    //transition: width .3s;
}

.active-2 {
    display: inline-block;
    color: white;
    text-decoration: none;

}

.active-2::after {
    content: '';
    display: block;
    /*width: 0;*/
    height: 2px;
    background: white;
    margin-top: 18px;
    transition: width .3s;
}

.active-2:hover::after {
    width: 100%;
    //transition: width .3s;
}


.font-color-title {
  color:#E65100;
}

.height-navbar {
  height: 80px;
}

.underline {
  text-decoration: underline;
}

.category:hover {
    background-color: #E65100;
}

.w3-hover-theme{color:#fff !important; background-color:#e65100 !important}

.border-line-top {
    border-top: 1px solid black;
}
</style>
