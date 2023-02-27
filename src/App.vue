<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppMain from './components/AppMain.vue'
import AppBlueMenu from './components/AppBlueMenu.vue';
export default{
  data(){
    return{

    }
  },
  components: { AppHeader, AppFooter, AppMain, AppBlueMenu }
};
</script>

<template>
 <AppHeader/>
 
 <AppMain/>

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
  max-width: 1000px;
  margin: 0 auto;
}


</style>
