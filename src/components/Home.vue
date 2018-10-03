<template>
  <div class="home">
    <!-- Navbar (sit on top) -->
    <div class="w3-top">
      <div class="w3-bar w3-black w3-wide w3-padding w3-card menu">
        <router-link to="/"><a class="w3-bar-item w3-button no-underline"><b>DRY SEED</b></a></router-link>
        <!-- Float links to the right. Hide them on small screens -->
        <div class="w3-right w3-hide-small">
          <router-link to="/projects"><a class="w3-bar-item w3-button">PROJECTS</a></router-link>
          <router-link to="/about"><a class="w3-bar-item w3-button">ABOUT</a></router-link>
        </div>
      </div>
    </div>
     <!-- Page content -->
    <div class="w3-content w3-padding" style="max-width:1564px">

      <!-- Project Section -->
     <!--  <div class="w3-container w3-padding-16 w3-left w3-row-padding" id="projects">
        <div class="w3-col l4">
          <button class="w3-button w3-black box-radius">ALL</button>
          <button class="w3-button w3-white w3-margin-right box-radius">F&B</button>
          <button class="w3-button w3-white w3-margin-right box-radius">SAAS</button>
          <button class="w3-button w3-white w3-margin-right box-radius">FURNITURE</button>
        </div> -->
      <!-- </div> -->

      <div class="w3-row-padding w3-padding-32 menu">
        <div class="w3-col l1 m2 s12 w3-margin-bottom">
          <div class="w3-display-container w3-left">
            <button class="w3-button w3-black box-radius">ALL</button>
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l5 m8 s12 w3-margin-bottom">
          <div class="w3-display-container w3-left">
            <button class="w3-button w3-white w3-margin-right box-radius">F&B</button>
            <button class="w3-button w3-white w3-margin-right box-radius">SAAS</button>
            <button class="w3-button w3-white w3-margin-right box-radius">FURNITURE</button>
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
    </div>

      <div class="w3-row-padding">
        <div class="w3-col l4 m6 w3-margin-bottom" v-for="user in users" :key="user.id">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Summer House</div> -->
            <img :src="require(`../assets/${user.url}`)" alt="House" style="width:100%">
            <span class="body-18px">{{ user.name}}</span>
          </div>
        </div>
     </div>
 <!-- End page content -->
    </div>
    <footer class="w3-center w3-light-grey w3-padding-32">
      <span class="caption">2018 Dryseed</span>
    </footer>

  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
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

</style>
