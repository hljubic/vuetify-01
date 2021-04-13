<template>
  <div class="about">
    <h1>This is an about page</h1>
    <sum-it n1="23" n2="37"></sum-it>

    <card-view title="Prva kartica" text="Ovo je moja prva komponenta"></card-view>
    <card-view title="Druga kartica" text="Ovo je moja prva komponenta"></card-view>
    <card-view title="Treća kartica" text="Ovo je moja prva komponenta"></card-view>
  </div>
</template>
<script>
import SumIt from '../components/SumIt.vue';
import CardView from '../components/CardView.vue';

export default {
  components: {
    CardView, SumIt
  }
}
</script>