<template>
  <!-- Navbar -->
  <div>
    <div class="w3-top">
      <ul class="w3-navbar w3-black w3-card-2 w3-left-align">
        <li class="w3-hide-medium w3-hide-large w3-opennav w3-right">
          <a class="w3-padding-large" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
        </li>
        <!-- <li><a href="#" class="w3-hover-none w3-hover-text-grey w3-padding-large">HOME</a></li> -->
        <li>
          <router-link to="/home" class="w3-hover-none w3-hover-text-grey w3-padding-large">Home</router-link>
        </li>
        <li><router-link to="/detailedpost" class="w3-padding-large">Band</router-link></li>
        <!-- <li class="w3-hide-small"><a href="/detailedpost" class="w3-padding-large">BAND</a></li> -->
        <li class="w3-hide-small"><a href="#tour" class="w3-padding-large">TOUR</a></li>
        <li class="w3-hide-small"><a href="#contact" class="w3-padding-large">CONTACT</a></li>
        <li><router-link to="/admin/login" class="w3-padding-large">Login</router-link></li>
        <li class="w3-hide-small w3-dropdown-hover">
          <a href="javascript:void(0)" class="w3-hover-none w3-padding-large" title="More">MORE <i class="fa fa-caret-down"></i></a>
          <div class="w3-dropdown-content w3-white w3-card-4">
            <a href="#">Merchandise</a>
            <a href="#">Extras</a>
            <a href="#">Media</a>
          </div>
        </li>
        <li class="w3-hide-small w3-right"><a href="javascript:void(0)" class="w3-padding-large w3-hover-red"><i class="fa fa-search"></i></a></li>
      </ul>
    </div>

    <!-- Navbar on small screens -->
    <div id="navDemo" class="w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
      <ul class="w3-navbar w3-left-align w3-black">
        <li><a class="w3-padding-large" href="#band">BAND</a></li>
        <li><a class="w3-padding-large" href="#tour">TOUR</a></li>
        <li><a class="w3-padding-large" href="#contact">CONTACT</a></li>
        <li><a class="w3-padding-large" href="#">MERCH</a></li>
      </ul>
    </div>
  </div>
</template>
