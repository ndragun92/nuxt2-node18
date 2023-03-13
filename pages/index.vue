<template>
  <div>
    <h1>Nuxt 2 Script Setup Example</h1>
    <button type="button" @click="counter++">Increase</button>
    <div>
      {{counter}}
    </div>
  </div>
</template>

<!--<script lang="ts">-->
<!--import Vue from 'vue'-->

<!--export default Vue.extend({-->
<!--  name: 'IndexPage',-->
<!--})-->
<!--</script>-->

<script lang="ts" setup>
import { ref } from "vue";

const counter = ref(0)
</script>
