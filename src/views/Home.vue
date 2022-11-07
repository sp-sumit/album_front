<script>
import About from '../components/abouts.vue';
import Base from '../components/base.vue';

export default{
    components:{
        Base,
        About
    }
}

</script>
<template>
    <div class="content">
        <Base></Base>
        <About></About>
    </div>
</template>
<style scoped>
    
  .content{
    /* width: 100%;
    display: flex; */
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
  }
</style>