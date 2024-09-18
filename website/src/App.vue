<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div class="">
      <a href="#"><img width="60px" src="https://a3gs.com.br/img/logo-A3GS-write.png" alt="foto" /></a>
    </div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">DDDD</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="search-bar">
      <input type="text" placeholder="Search...">
    </div>

  </header>

  <main>
    
  </main>

  <footer>
    <p style="font-size: 10pt;"> Todos os direito a André Felipe - 2024</p>
  </footer>
</template>

<style scoped>
header {
  /* line-height: 1.5; */
  width: 100%;
  background-color: #333;
  color: #fff;
  padding: 10px 2rem;
 
  display: flex;
  justify-content: space-between;
  align-items: center; 

  nav{
    display: flex;
    margin: 0;
    padding: 0;
    ul{
      margin: 0;
      padding: 0;
      list-style-type: none;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      li:hover{
        border: 1px solid #0b746b;
      }
      li{
        padding: 5px 20px;
        border-radius: 10px;
        border: 1px solid #00000000;
        
        a{
          color: #fff;
          text-decoration: none;
        }
      }
    }
  }
}


footer {
  width: 100%;
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: center;
  position: absolute;
  bottom: 0;
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
