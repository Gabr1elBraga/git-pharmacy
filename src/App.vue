<template>
  <div>
    <NavBar :logo="logo_src" :alt="app_name" />
    <div>
      <router-view></router-view>
    </div>
    <Footer />
  </div>
</template>


<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    NavBar,
    Footer
  },
  data:function() {
    return {
      logo_src: '/img/logo_farmacia.png',
      app_name: 'Make your burguer'

    }
  }

}
</script>

<style>
* {
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main_container {
  margin: 50px;
  min-height: 250px;
}

h1 {
  text-align: center;
  font-size: 40px;
  margin-bottom: 30px;
  color: #222;
}
</style>
