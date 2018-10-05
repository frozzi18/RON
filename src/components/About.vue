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
          <router-link to="/projects"><a class="w3-bar-item margin-top-navbar cool-link">PROJECTS</a></router-link>
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

      <div class="w3-row-padding margin-top-process">
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
            <h3><span class="font-color-title">Research</span></h3>
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
            <h3><span class="font-color-title">Design</span></h3>
            <p>Every pixel counts. We make sure your website is as beautiful as it is functional. Also, we do this based on research mixed with our creativity.</p>            <!-- <h3>Super Offers</h3> -->
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
            <h3><span class="font-color-title">Develop</span></h3>
            <p>We promise that your website will be responsive and fast. So relax, you will not losing potential customer due to a chaotic website.</p>
          </div>
        </div>
        <div class="w3-col l2 m1 w3-margin-bottom">
          <div class="w3-display-container">
            <!-- <h3>Super Offers</h3> -->
          </div>
        </div>
        <div class="w3-col l2 m5 w3-margin-bottom">
          <div class="w3-display-container w3-left-align">
            <h3><span class="font-color-title">Evaluate</span></h3>
            <p>Seeing is believing. After your site is online, we will monitor your website performance to see the actual performance and spot hidden problem.</p>
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
               <a href="mailto:hello@dryseed.agency" class="no-underline">hello@dryseed.agency</a>
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
               <a href="tel:+6280000000" class="no-underline">+62 8000 0000</a>
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
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black">Twitter</div></router-link>
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black">Instagram</div></router-link>
              </div>
              <div class="w3-row">
                <router-link to="/projects"><div class="w3-col s4 w3-left-align w3-black">Blog</div></router-link>
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

.height-navbar {
  height: 80px;
}

.margin-top-navbar{
  padding-top: 25px;
}

.margin-top-welcome{
  padding-top: 118px;
}

/*.margin-top-process{
  padding-top: 218px;
  padding-bottom: 123px;
}*/

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

.no-underline {
  text-decoration: none;
}

.font-color-title {
  color:#E65100;
}
</style>
