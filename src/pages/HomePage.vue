<template>
  <div class="container-fluid">
   
    <section class="row">   
      <Title />
    </section>
    <section class="row">
      <Portfolio />
    </section>
  </div>
</template>

<script>
import Portfolio from '../components/Portfolio.vue';
import Title from '../components/Title.vue';


export default {
  setup() {
    return {};
  },
  components: { Portfolio, Title }
}
</script>

<style scoped lang="scss"></style>
