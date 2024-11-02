

<template>

  <Header>
        
</Header>

<div class="containerIndex">
  

  <input type="text" 
    
    class="searchInput"
  placeholder="Busca un idioma. . . "  />


</div>


  <Footer></Footer>
  
</template>

<script setup>


import Header from './Header.vue';
import Footer from './components/Footer.vue'; 







</script>

<style scoped>


.containerIndex {
  display: flex;
  flex-direction: column;
  padding: 10px 20px;
  border: 1px solid green;
  align-items: center;
  justify-content: flex-start;
  width: 80%;
  margin: 0 auto;
  min-height: 240px;
  height: auto;
}

.searchInput{
  width: 40%;
  padding: 12px;
  margin-top: 10px;
  border: 1px solid gray;
  border-radius: 4px;
  font-size: 1.2em;
  height: 20px;

}



</style>