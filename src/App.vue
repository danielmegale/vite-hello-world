<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default{ components: { AppTitle, AppHero } }
</script>

<template>
  <div class="container">
    <AppTitle/>
    <AppHero/>
  </div>
</template>

<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.container{
	max-width:1080px;
	margin:0px auto;

}
</style>