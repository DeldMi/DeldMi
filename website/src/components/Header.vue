<script setup lang="ts">

import { RouterLink as Link, useRoute } from 'vue-router'


// defineProps<{
//   router: string,
//   txt: string
// }>()

const route = useRoute();

function actives(router: any, route: any, className: any){
  if (router.name === route){
    return className
  }
}



</script>

<template>
  <div id="header">
    <div class="logo" style="height: 60px;">
      <Link to="/" style="background: none;">
        <img height="100%" src="https://a3gs.com.br/img/logo-A3GS-write.png" alt="foto" />
      </Link>
    </div>
    <nav id="menu">
      <ul>
        <li>
          <Link  to="/" :class="{ active: route.name === 'Home'}">Home</Link>
        </li>
        <li>
          <Link to="/about" :class="{ active: route.name === 'About' }" >About</Link>
        </li>
        <li><Link to="/contact" :class="{ active: route.name === 'Contact' } ">Contact</Link></li>
      </ul>
    </nav>
    <div class="search-bar">
      <!-- <input type="text" placeholder="Search..."> -->
      
    </div>
  </div>
</template>




<style scoped>
.active {
  
  background-color: #0b746b;
  transition: cubic-bezier(0.075, 0.82, 0.165, 1);
}
#header {
  /* line-height: 1.5; */
  width: 100%;
  background-color: var(--color-background-mute);
  color: #fff;
  padding: 10px 2rem;

  display: flex;
  justify-content: space-between;
  align-items: center;

  nav {
    display: flex;
    margin: 0;
    padding: 0;

    ul {
      margin: 0;
      padding: 0;
      list-style-type: none;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;

      a:hover   {
        border: 1px solid #0b746b;
      }
        a {
          padding: 5px 20px;
          border-radius: 10px;
          color: var(--color-text);
          border: 1px solid #00000000;
          text-decoration: none;
        }
      
    }
  }
}

/* @media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    align-items: center;
    justify-content: space-between;
    

  }
}
*/
</style>
