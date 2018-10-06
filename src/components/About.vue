<template>
  <div class="about">
    <!-- Navbar (sit on top) -->
    <div class="w3-top">
      <div class="w3-bar w3-white w3-padding w3-card menu">
        <div class="height-navbar">
         <router-link to="/"><a class="w3-bar-item no-underline margin-top-navbar cool-link">DRY SEED
         </a></router-link>
        <!-- Float links to the right. Hide them on small screens -->
         <div class="w3-right w3-hide-small">
          <router-link to="/"><a class="w3-bar-item margin-top-navbar cool-link">PROJECTS</a></router-link>
          <router-link to="/about"><a class="w3-bar-item margin-top-navbar"><span class="active">ABOUT</span></a></router-link>
         </div>
        </div>
      </div>
    </div>
     <!-- Page content -->
    <div class="w3-content w3-padding" style="max-width:1564px">

      <div>
      <span class="w3-button w3-xxlarge w3-white w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></span>
      <div class="w3-clear"></div>
      <header class="w3-center w3-margin-bottom">
        <div class="headline-smallest margin-top-welcome">WELCOME TO DRYSEED</div>
        <img src="../assets/illustration-geometric.svg" alt="House" style="width:20%">
        <div class="w3-row-padding">
        <div class="w3-col l3 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col s12 m8 l6 w3-margin-bottom">
          <div class="w3-display-container">
            <span class="body-18px">We are creative studio specialising in Web Design & Development.</span><br><br>
            <span class="body-18px">We help Vendor Businesses: Catering, Event Organizer, Business Equipment Provider, etc; and early stage SaaS Startup to build website that represent their brand and help them grow their customer base in this connected world.</span>
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

      <div class="w3-row-padding w3-padding-48 margin-top-process">
        <div class="w3-col l4 m2 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l4 m8 w3-margin-bottom">
          <div class="w3-display-container">
            <span class="headline-smallest err">OUR PROCESS</span>
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
            <span class="font-color-title headline-medium-title">Research</span><br><br>
            <span class="body-18px">We always put business goal above all in creating a website. Therefore, we do research before we do anything else.</span>
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <span class="font-color-title headline-medium-title">Design</span><br><br>
            <span class="body-18px">Every pixel counts. We make sure your website is as beautiful as it is functional. Also, we do this based on research mixed with our creativity.</span>
          </div>
        </div>
        <div class="w3-col l2 m6 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
        <div class="w3-col l2 m6 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
     </div>

      <div class="w3-row-padding">
        <div class="w3-col l2 m0 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <span class="font-color-title headline-medium-title">Develop</span><br><br>
            <span class="body-18px">We promise that your website will be responsive and fast. So relax, you will not losing potential customer due to a chaotic website.</span>
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <span class="font-color-title headline-medium-title">Evaluate</span><br><br>
            <span class="body-18px">Seeing is believing. After your site is online, we will monitor your website performance to see the actual performance and spot hidden problem.</span>
          </div>
        </div>
        <div class="w3-col l2 m0 w3-margin-bottom">
          <div class="w3-display-container">
          </div>
        </div>
     </div>
    </div>
 <!-- End page content -->
    <footer class="w3-center w3-light-grey w3-padding-32">
      <div class="w3-center w3-black w3-padding-64">
         <div class="w3-row-padding">
           <div class="w3-col l1 m1 w3-margin-bottom">
             <div class="w3-display-container">
             </div>
           </div>
           <div class="w3-col l2 m5 w3-margin-bottom">
             <div class="w3-display-container w3-left-align">
               <div class="w3-padding-32"><span class="caption">New Inqueries</span><br></div>
               <a href="mailto:hello@dryseed.agency" class="no-underline body-18px">hello@dryseed.agency</a>
             </div>
           </div>
           <div class="w3-col l2 m1 w3-margin-bottom">
             <div class="w3-display-container">
             </div>
           </div>
           <div class="w3-col l2 m5 w3-margin-bottom">
             <div class="w3-display-container w3-left-align">
               <div class="w3-padding-32"><span class="caption">Phone</span><br></div>
               <a href="tel:+6280000000" class="no-underline body-18px">+62 8000 0000</a>
             </div>
           </div>
           <div class="w3-col l1 m1 w3-margin-bottom">
             <div class="w3-display-container">
             </div>
           </div>
           <div class="w3-col l3 m6 w3-margin-bottom">
             <div class="w3-display-container">
              <div class="w3-row">

                <div class="w3-col s12 w3-left-align"><div class="w3-padding-32"><span class="caption">Connect</span><br></div></div>
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black body-18px">Twitter</div></router-link>
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black body-18px">Instagram</div></router-link>
              </div>
              <div class="w3-row">
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black body-18px">Blog</div></router-link>
              </div>
             </div>
           </div>
         </div>
      </div>
       <div class="w3-padding-32"><span class="caption">2018 Dryseed</span></div>
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

.height-navbar {
  height: 80px;
}

.margin-top-navbar{
  padding-top: 25px;
}

.margin-top-welcome{
  padding-top: 118px;
}

.err {
    display: inline-block;
    position:relative;
    background: url(http://i.imgur.com/HlfA2is.gif) bottom repeat-x;
}

</style>
