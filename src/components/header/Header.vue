<script setup>
import { ref } from 'vue';
import { RouterLink } from 'vue-router';

const isActive = ref(false);
const toggleNavbar = () => {
  isActive.value = !isActive.value;
};

</script>

<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <RouterLink class="navbar-item" to="/">
           <svg width="256px" height="256px" viewBox="0 -13 64 64" xmlns="http://www.w3.org/2000/svg" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g id="Group_164" data-name="Group 164" transform="translate(-487 -744.409)"> <g id="Group_153" data-name="Group 153"> <path id="Path_258" data-name="Path 258" d="M495,767.555v-2.146a7,7,0,0,1,7-7h18.2a5.005,5.005,0,0,1,3.8,1.747l5.46,6.211" fill="#e24646"></path> <path id="Path_259" data-name="Path 259" d="M496,767.555h-2v-2.146a8.009,8.009,0,0,1,8-8h18.2a6,6,0,0,1,4.559,2.1l5.452,6.2-1.5,1.32-5.46-6.211a4.008,4.008,0,0,0-3.049-1.407H502a6.006,6.006,0,0,0-6,6Z"></path> </g> <g id="Group_154" data-name="Group 154"> <path id="Path_260" data-name="Path 260" d="M500,776.409a5,5,0,0,1-5-5v-5h43.219A4.781,4.781,0,0,1,543,771.19v.438a4.782,4.782,0,0,1-4.781,4.781H500Z" fill="#e24646"></path> <path id="Path_261" data-name="Path 261" d="M538.219,777.409H500a6.007,6.007,0,0,1-6-6v-6h44.219A5.788,5.788,0,0,1,544,771.19v.437A5.789,5.789,0,0,1,538.219,777.409Zm-42.219-10v4a4,4,0,0,0,4,4h38.219A3.786,3.786,0,0,0,542,771.627v-.437a3.785,3.785,0,0,0-3.781-3.781Z"></path> </g> <g id="Group_155" data-name="Group 155"> <circle id="Ellipse_42" data-name="Ellipse 42" cx="3.975" cy="3.975" r="3.975" transform="translate(528.53 771.459)" fill="#e24646"></circle> <path id="Path_262" data-name="Path 262" d="M532.505,771.459a3.975,3.975,0,1,1-3.975,3.975,3.975,3.975,0,0,1,3.975-3.975m0-2a5.975,5.975,0,1,0,5.974,5.975,5.982,5.982,0,0,0-5.974-5.975Z"></path> </g> <g id="Group_156" data-name="Group 156"> <circle id="Ellipse_43" data-name="Ellipse 43" cx="3.975" cy="3.975" r="3.975" transform="translate(500.53 771.459)" fill="#e24646"></circle> <path id="Path_263" data-name="Path 263" d="M504.505,771.459a3.975,3.975,0,1,1-3.975,3.975,3.975,3.975,0,0,1,3.975-3.975m0-2a5.975,5.975,0,1,0,5.974,5.975,5.982,5.982,0,0,0-5.974-5.975Z"></path> </g> <g id="Group_157" data-name="Group 157"> <line id="Line_95" data-name="Line 95" x1="3" transform="translate(518 770.409)" fill="#e24646"></line> <path id="Path_264" data-name="Path 264" d="M521,771.409h-3a1,1,0,0,1,0-2h3a1,1,0,0,1,0,2Z"></path> </g> <g id="Group_158" data-name="Group 158"> <line id="Line_96" data-name="Line 96" x1="62" transform="translate(488 781.409)" fill="#e24646"></line> <path id="Path_265" data-name="Path 265" d="M550,782.409H488a1,1,0,0,1,0-2h62a1,1,0,0,1,0,2Z"></path> </g> <g id="Group_159" data-name="Group 159"> <line id="Line_97" data-name="Line 97" x1="8" transform="translate(528 753.409)" fill="#e24646"></line> <path id="Path_266" data-name="Path 266" d="M536,754.409h-8a1,1,0,0,1,0-2h8a1,1,0,0,1,0,2Z"></path> </g> <g id="Group_160" data-name="Group 160"> <line id="Line_98" data-name="Line 98" y2="2" transform="translate(536 745.409)" fill="#e24646"></line> <path id="Path_267" data-name="Path 267" d="M536,748.409a1,1,0,0,1-1-1v-2a1,1,0,0,1,2,0v2A1,1,0,0,1,536,748.409Z"></path> </g> <g id="Group_161" data-name="Group 161"> <line id="Line_99" data-name="Line 99" x1="2" transform="translate(542 753.409)" fill="#e24646"></line> <path id="Path_268" data-name="Path 268" d="M544,754.409h-2a1,1,0,0,1,0-2h2a1,1,0,0,1,0,2Z"></path> </g> <g id="Group_162" data-name="Group 162"> <line id="Line_100" data-name="Line 100" x1="1.414" y2="1.414" transform="translate(540.293 747.702)" fill="#e24646"></line> <path id="Path_269" data-name="Path 269" d="M540.293,750.116a1,1,0,0,1-.707-1.707L541,746.995a1,1,0,0,1,1.414,1.414L541,749.823A1,1,0,0,1,540.293,750.116Z"></path> </g> <g id="Group_163" data-name="Group 163"> <line id="Line_101" data-name="Line 101" x2="1.414" y2="1.414" transform="translate(530.293 747.702)" fill="#e24646"></line> <path id="Path_270" data-name="Path 270" d="M531.707,750.116a1,1,0,0,1-.707-.293l-1.414-1.414A1,1,0,0,1,531,746.995l1.414,1.414a1,1,0,0,1-.707,1.707Z"></path> </g> </g> </g></svg>
        </RouterLink>
  
        <a
          role="button"
          class="navbar-burger"
          :class="{ 'is-active': isActive }"
          aria-label="menu"
          aria-expanded="false"
          @click="toggleNavbar"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
  
      <div class="navbar-menu" :class="{ 'is-active': isActive }">
      
        <div class="navbar-start">
          <RouterLink class="navbar-item" to="/">Home</RouterLink>
          <RouterLink class="navbar-item" to="/carlisiting">Car Listing</RouterLink>
          <RouterLink class="navbar-item" to="/paymentcalc">Payment Calculator</RouterLink>
          <RouterLink class="navbar-item" to="/Located">Located</RouterLink>
        </div>
      </div>
    </nav>
  </template>
  



  <style scoped>
  /* Optional: Custom background color */
  svg{
    width: 50px;
    height: 50px;
  }
  .navbar {
  background-color: #2B303A;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.navbar-item {
  color: white;
  font-weight: 500;
  font-size: 1rem;
  padding: 0.75rem 1rem;
  transition: background-color 0.2s ease;
}

.navbar-item:hover {
  background-color: #515765;
  color: #f5f5f5;
}

.navbar-start {
  align-items: center;
}

.navbar-menu{
    margin-bottom: 10px;
}


.navbar-burger{
  color: #f5f5f5;
}
@media screen and  (max-width: 970px){

  .navbar-menu{
    width: 100%;
  }

  .navbar-item{
    color: black;
    /* text-align: right; */
  }
}
  </style>
  