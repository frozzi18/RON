<template>
  <div class="show">
    <!-- Navbar (sit on top) -->
    <div class="w3-top">
      <div class="w3-bar w3-black w3-wide w3-padding w3-card">
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

      <div class="w3-row-padding modif-padding">
      <div class="w3-half w3-container">
        <img src="../assets/Ceremony-Coffee-Roasters-thumb.png" alt="House" style="width:60%">
        <h3 class="w3-text-grey w3-large"><a href="#about">See in full size</a></h3>
      </div>
      <div class="w3-half w3-container w3-xlarge w3-text-grey w3-left-align">
        <h3 class="w3-text-grey">Super Offer</h3>
        <p class="">We build design teams
        - we break things down and build it better
        - we deliver the best of solutions</p>
        <p>InShock means powerfull simplicity</p>
      </div>
      </div>

      <!-- Project Section -->
      <div class="w3-container w3-padding-16 w3-left">
        <button class="w3-button w3-black box-radius">ALL</button>
        <button class="w3-button w3-white w3-margin-right box-radius">F&B</button>
        <button class="w3-button w3-white w3-hide-small w3-margin-right box-radius">SAAS</button>
        <button class="w3-button w3-white w3-hide-small w3-margin-right box-radius">FURNITURE</button>
        <!-- <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Projects</h3> -->
      </div>

      <div class="w3-row-padding">
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Summer House</div> -->
            <img src="../assets/Ceremony-Coffee-Roasters-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Brick House</div> -->
            <img src="../assets/death-wish-coffee-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Renovated</div> -->
            <img src="../assets/Google-Home-Mini-Donut-Shop-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
    <!-- </div> -->

      <!-- <div class="w3-row-padding"> -->
        <div class="w3-col l4 m6 w3-margin-bot3om">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Summer House</div> -->
            <img src="../assets/MonkeyLearn-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Renovated</div> -->
            <img src="../assets/Maison-Riviera-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
     <!-- </div> -->

      <!-- <div class="w3-row-padding"> -->
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Summer House</div> -->
            <img src="../assets/MonkeyLearn-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Brick House</div> -->
            <img src="../assets/nello-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
        <div class="w3-col l4 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <div class="w3-display-topleft w3-black w3-padding">Renovated</div> -->
            <img src="../assets/netguru-design-process-thumb.png" alt="House" style="width:100%">
            <h3>Super Offers</h3>
          </div>
        </div>
     </div>
 <!-- End page content -->
    </div>
    <footer class="w3-center w3-light-grey w3-padding-32" id="about">
      <p>2018 Dryseed</p>
    </footer>

  </div>
</template>

<script>
export default {
  name: 'Show',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
  padding: 50px 50px;
}

.no-underline {
  text-decoration: none;
}
</style>
