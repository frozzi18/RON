<template>
  <div class="show">
    <!-- Navbar (sit on top) -->
    <div class="w3-top">
      <div class="w3-bar w3-black w3-padding w3-card menu">
        <div class="height-navbar">
         <router-link to="/"><a class="w3-button w3-bar-item no-underline margin-top-navbar w3-hover-black cool-link-2">DRY SEED
         </a></router-link>
        <!-- Float links to the right. Hide them on small screens -->
         <div class="w3-right w3-hide-small">
          <router-link to="/"><a class="w3-button w3-bar-item margin-top-navbar w3-hover-black"><span class="active-2">PROJECTS</span></a></router-link>
          <router-link to="/about"><a class="w3-button w3-bar-item margin-top-navbar cool-link-2 w3-hover-black">ABOUT</a></router-link>
         </div>
        </div>
      </div>
    </div>
     <!-- Page content -->
    <div class="w3-content w3-padding" style="max-width:1564px">

      <div class="w3-row-padding modif-padding">
      <div class="w3-half w3-container">
        <img src="../assets/Ceremony-Coffee-Roasters-thumb.png" alt="House" style="width:60%">
        <h3 class="w3-text-grey w3-large"><a href="#about"><span class="body-18px link-color">See in full size</span></a></h3>
      </div>
      <div class="w3-col l4 w3-container w3-xlarge w3-text-grey w3-left-align">
        <span class="w3-text-black headline-normal">{{ users[0].name}}</span><br>
        <a href="#about"><span class="caption link-color-visit">Visit Website</span></a><br>
        <span class="body-18px">{{description_1}}</span>
        <br>
        <br>
        <span class="body-18px">{{description_2}}</span>
      </div>
      </div>

      <!-- Project Section -->
      <div class="w3-container w3-padding-16 w3-left menu">
        <button class="w3-button box-radius w3-hover-theme">ALL</button>
        <button class="w3-button w3-margin-right box-radius underline w3-hover-white">F&B</button>
        <button class="w3-button w3-hide-small w3-margin-right box-radius underline w3-hover-white">SAAS</button>
        <button class="w3-button w3-hide-small w3-margin-right box-radius underline w3-hover-white">FURNITURE</button>
        <!-- <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Projects</h3> -->
      </div>


      <div class="w3-row-padding">
        <div class="w3-col l4 m6 w3-margin-bottom" v-for="user in users" :key="user.id">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Summer House</div> -->
            <router-link to="/projects"><img :src="require(`../assets/${user.url}`)" alt="House" style="width:100%" class="w3-hover-opacity border-line-top"></router-link>
            <div class="w3-padding-16"><span class="body-18px">{{ user.name}}</span></div>
          </div>
        </div>
     </div>
 <!-- End page content -->
    </div>
    <footer class="w3-center w3-white w3-padding-64 border-line-top" id="about">
      <span class="caption">2018 Dryseed</span>
    </footer>

  </div>
</template>
<!-- http://localhost:8080/static/img/death-wish-coffee-thumb.c685fde.png -->
<!-- http://localhost:8080/static/img/Ceremony-Coffee-Roasters-thumb.png -->

<script>
export default {
  name: 'show',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      description_1: 'Suara bulan merdu digarasi yang basah. Petikan sitar yang lincah dalam tentak tabu, kau sungguh kontras malam ini. Mengalun disela rintik rindu yang sengit, menarilah denganku.',
      description_2: 'Pesanku pada malam-malam yang tenang dan sunyi. Mintalah lewat doa yang kau ucap dengan mesra. Ialah Sang Maha, Pelukan-Nya menyentuh sukma',
      users: [
        { name: 'Ceremony Coffe Roaste', url: 'Ceremony-Coffee-Roasters-thumb.png' },
        { name: 'Death Wish Coffe', url: 'death-wish-coffee-thumb.png' },
        { name: 'Maison Riviera', url: 'Maison-Riviera-thumb.png' },
        { name: 'Recipelist', url: 'Recipelist-thumb.png' },
        { name: 'Google Home Mini', url: 'Google-Home-Mini-Donut-Shop-thumb.png' },
        { name: 'J&T Real Estate', url: 'J-T-Real-Estate-thumb.png' },
        { name: 'Monkey Learn', url: 'MonkeyLearn-thumb.png' },
        { name: 'Nello', url: 'nello-thumb.png' },
        { name: 'Net Guru Design Process', url: 'netguru-design-process-thumb.png' }
      ]
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.box-radius {
  border-radius: 25px;
}

h1, h2, h3, h4, h5, h6 {
  font-family: 'Montserrat', sans-serif;
}

.modif-padding {
  padding: 150px 50px;
}

.height-navbar {
  height: 80px;
}

.margin-top-navbar{
  padding-top: 25px;
}

.link-color{
  color: #E65100;
}

.link-color-visit{
  color: #9E9E9E;
}


.color-font{
  color: #000000;
}
</style>
