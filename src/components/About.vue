<template>
  <div class="about">
    <!-- Navbar (sit on top) -->
    <div class="w3-top">
      <div class="w3-bar w3-white w3-wide w3-padding w3-card menu">
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

      <div class="w3-opacity">
      <span class="w3-button w3-xxlarge w3-white w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></span>
      <div class="w3-clear"></div>
      <header class="w3-center w3-margin-bottom">
        <h1><b>WELCOME TO DRYSEED</b></h1>
        <img src="../assets/illustration-geometric.svg" alt="House" style="width:20%">
        <div class="w3-row-padding">
        <div class="w3-col l3 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col s12 m8 l6 w3-margin-bottom">
          <div class="w3-display-container">
            <h4>We are creative studio specialising in Web Design & Development.</h4><br>
            <p>We help Vendor Businesses: Catering, Event Organizer, Business Equipment Provider, etc; and early stage SaaS Startup to build website that represent their brand and help them grow their customer base in this connected world.</p>
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l3 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        </div>
      </header>
      </div>

      <div class="w3-row-padding">
        <div class="w3-col l4 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l4 m8 w3-margin-bottom">
          <div class="w3-display-container">
            <h4>OUR PROCESS</h4>
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l4 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
    </div>

      <div class="w3-row-padding">
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <h3>Research</h3>
            <p>We always put business goal above all in creating a website. Therefore, we do research before we do anything else.</p>
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <h3>Research</h3>
            <p>We always put business goal above all in creating a website. Therefore, we do research before we do anything else.</p>            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m6 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
     </div>

      <div class="w3-row-padding">
        <div class="w3-col l2 m0 w3-margin-bottom">
          <div class="w3-display-container">
             <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <h3>Research</h3>
            <p>We always put business goal above all in creating a website. Therefore, we do research before we do anything else.</p>
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <h3>Research</h3>
            <p>We always put business goal above all in creating a website. Therefore, we do research before we do anything else.</p>
          </div>
        </div>
        <div class="w3-col l2 m0 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
     </div>
 <!-- End page content -->
    </div>
    <footer class="w3-center w3-light-grey w3-padding-32">
      <div class="w3-center w3-black w3-padding-64">
         <div class="w3-row-padding">
           <div class="w3-col l1 m1 w3-margin-bottom">
             <div class="w3-display-container">
               <!-- <h3>Super Offers</h3> -->
             </div>
           </div>
           <div class="w3-col l2 m5 w3-margin-bottom">
             <div class="w3-display-container w3-left-align">
               <h3>New Inqueries</h3>
               <p>hello@dryseed.agency</p>
               <!-- <h3>Super Offers</h3> -->
             </div>
           </div>
           <div class="w3-col l2 m1 w3-margin-bottom">
             <div class="w3-display-container">
               <!-- <h3>Super Offers</h3> -->
             </div>
           </div>
           <div class="w3-col l2 m5 w3-margin-bottom">
             <div class="w3-display-container w3-left-align">
               <h3>Phone</h3>
               <p>+62 8000 0000</p>
             </div>
           </div>
           <div class="w3-col l1 m1 w3-margin-bottom">
             <div class="w3-display-container">
               <!-- <h3>Super Offers</h3> -->
             </div>
           </div>
           <div class="w3-col l3 m6 w3-margin-bottom">
             <div class="w3-display-container">
              <div class="w3-row">
                <div class="w3-col s12 w3-left-align"><h3>Connect</h3></div>
                <div class="w3-col s4 w3-left-align"><a href="#home" class="w3-button w3-black">Twitter</a></div>
                <div class="w3-col s4 w3-left-align"><a href="#home" class="w3-button w3-black">Instagram</a></div>
              </div>
              <div class="w3-row">
                <div class="w3-col s4 w3-left-align"><a href="#home" class="w3-button w3-black">Blog</a></div>
              </div>
             </div>
           </div>
         </div>
      </div>
       <span class="caption">2018 Dryseed</span>
    </footer>

  </div>
</template>

<script>
export default {
  name: 'About',
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

</style>
