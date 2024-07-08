<script>
import AppHeader from './components/AppHeader.vue'
export default{
  name:'app',
  components:{
    AppHeader,
  }
}
</script>

<template>
  <AppHeader/>
  
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables';
@use './styles/partials/mixins';

</style>
