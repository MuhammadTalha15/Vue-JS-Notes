<script setup>
import { ref, watch, watchEffect } from 'vue';

const count = ref(0);

</script>

<template>
  <button class="btn" @click="count++">
    The Count is {{ count }}
  </button>
</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.btn{
  height: 5vmax;
  width: 15vmax;
  cursor: pointer;
  font-size: 1.1vmax;
}
</style>
