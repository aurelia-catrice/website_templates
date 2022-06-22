<script>
import navbar from './components/navbar.vue'
import home from './components/home.vue'
import navfooter from './components/navfooter.vue'
import contact from './components/contact.vue'
import sectionleft from './components/section-left.vue'
import sectionright from './components/section-right.vue'
import list from './components/list.vue'

export default {
  components: {
    navbar,
    navfooter,
    contact,
    sectionleft,
    sectionright,
    list,
    home
  }
}
</script>

<template>

  <navbar/>
  <home/>
  <sectionleft/>
  <sectionright/>
  <list/>
  <contact/>
  <navfooter/>

</template>

<style>

@import './assets/base.css';


@media (max-width: 700px) {
  .image-left, .image-right {
    display: none;
  }
  .col-padding > img {
    display: flex;
    width: 300px;
    height: 230px;
  }
}
@media (max-width: 530px) {
  .bar > .bar-left {
    display: none;
  }
  .image-wide {
    display: none;
  }
  .container-img {
    margin-top: 50px;

  }
  .container-in-bottomleft > h1{
    opacity: 80%;
  }
}

</style>
