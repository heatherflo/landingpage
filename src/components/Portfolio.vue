<template>
  




  <div class="font col-12">

    <p class="text-center m-3">Applications</p>
  </div>
<div class="d-flex col-12 m-3 justify-content-center ">
      <p>Keepr</p>
        <img class=" mx-2 img-fluid keepr" :src="'src/assets/img/keepr.png'" alt="screenshot of KeeprAp">
    
        <p>allSpice</p>
        <img class="mx-2 img-fluid keepr" :src="'src/assets/img/keepr.png'" alt="screenshot of KeeprAp">
    
    <p>Tower</p>
    <img class=" mx-2 img-fluid keepr" :src="'src/assets/img/keepr.png'" alt="screenshot of KeeprAp">
    
  </div>

<section class="row">
  <div class="font">

<p class="m-3 text-center m-3">Pictures</p>
</div>
</section>

      

    

  
</template>


<script>

export default {
  setup() {
    return {}
  }
};
</script>


<style lang="scss" scoped>



.keepr{
  height: 20vh;
  width: auto;
}
.font{
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 75px;
}

</style>