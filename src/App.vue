
<script>
import HomeComp from './components/HomeComp.vue';
import ProyectPage from './components/ProyectPage.vue';
import NotFound from './components/NotFound.vue';
import TeamPage from './components/TeamPage.vue';

const routes = {
  '/': HomeComp,
  '/proyects': ProyectPage,
  '/team': TeamPage
}

export default {
  name: 'App',
  data() {
    return {
      currentPath: window.location.hash
    }
  },
  computed:{
    currentView(){
      return routes[this.currentPath.slice(1) || '/'] || NotFound
    }
  },
  mounted(){
    window.addEventListener('hashchange', ()=>{
      this.currentPath = window.location.hash
    })
  }

}
</script>

<template>

  <div>
        <header class="header">
            
            <img src="./assets/mexico.png" alt="mexico" class="header_icon">
            <p>ES</p>
            <i class="uil uil-angle-down"></i>
        </header>
        <nav>
            <a href="#/">
              <img src="./assets/logo_blanco.png" alt="logo" class="cumbre_logo">
            </a>
            <div class="nav_title">
                <a href="#/team">¿Quiénes somos?</a>
            </div>
            <div class="nav_title">
                <a href="#/proyects">Proyectos</a>
            </div>
            <div class="nav_title">
                <p>¿Cómo ayudar?</p>
            </div>
            <div class="nav_title contact_title">
                <p>Contáctanos</p>
            </div>
        </nav>
  </div>
  <component :is="currentView"/>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin:0;
}
body{
  margin:0;
}
.header {
    height: 24px;
    display: flex;
    align-items: center;
    column-gap: 4px;
    justify-content: right;

    }

    .header_icon{
    height: 100%;
    }

    nav{
    background-color: black;
    height: 104px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    
    }

    .cumbre_logo{
    width: 180px;
    }

    .nav_title{
    color:white;
    margin: 0;
    position: relative;
    bottom: -20px;
    font-weight: bold;

    }

    .contact_nav{
    color: black;
    background-color: white;
    }
    .contact_nav p{
    padding: 4px 20px;
    margin: 0;
    }
    a{
      text-decoration: none;
      color: white;
    }
</style>
