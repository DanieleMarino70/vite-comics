<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppMain from './components/AppMain.vue'
import AppBlueMenu from './components/AppBlueMenu.vue';


import headerLinks from './data/headerLinks.js'
import comics from './data/comics.js'
export default{
  data(){
    return{
      headerLinks,
      comics,
    }
  },
  components: { AppHeader, AppFooter, AppMain, AppBlueMenu }
};
</script>

<template>
 <AppHeader :headerLinks="headerLinks"/>
 
 <AppMain :comics="comics"/>

 <AppBlueMenu/>
    
  <AppFooter/>
</template>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.container{
  max-width: 1400px;
  margin: 0 auto;
}

ul {       
  list-style: none;         
}
li{
  text-decoration: none;
}



</style>
