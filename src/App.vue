<template>

<!-- slider stylesheet -->
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.1.3/assets/owl.carousel.min.css"/>

  <!-- bootstrap core css -->
  <link rel="stylesheet" type="text/css" href="css/bootstrap.css"/>

  <!-- fonts style -->
  <link href="https://fonts.googleapis.com/css?family=Dosis:400,500|Poppins:400,700&amp;display=swap" rel="stylesheet"/>
  <!-- Custom styles for this template -->
  <link href="css/style.css" rel="stylesheet"/>
  <!-- responsive style -->
  <link href="css/responsive.css" rel="stylesheet"/>
  
  

<router-view></router-view>
<contact-view></contact-view>

</template>

<style>
    @import './css/style.css';
    @import './css/responsive.css';
    @import './css/bootstrap.css';
 </style>

<script>
import ContactView from '../src/components/Contact.vue'
import SliderView from '../src/components/Slider.vue'

export default {
  components: {
    SliderView,
    ContactView
  }
}
</script>

<style>
    .form-control {
        background: rgb(230, 230, 230);
        border: 0;
    }
    .form-control:focus {
        background: rgb(216, 216, 216);
        border: 0;
    }
</style>

