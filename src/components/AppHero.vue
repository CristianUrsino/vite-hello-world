<template>
    <div class="container jumbotron">
        <div class="d-flex justify-content-center align-items-center align-content-center flex-column h-100">
            <div class="mb-4">
                <figure class="me-5"><img src="../../public/Vue.js_Logo_2.svg.png" alt="icona vue"></figure>
                <figure><img src="../../public/download.png" alt="icona boolean"></figure>
            </div>
            <AppTitle/>
        </div>
    </div>
</template>
  
<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppHero',
        components:{
            AppTitle,
        },
        data() {
          return {
          };
        }
    };
</script>
  
<style lang="scss" scoped>
figure{
    width: 225px;
    display: inline-block;
}
img{
    width: 225px;
}
.jumbotron{
    height: 100vh;
}
</style>
