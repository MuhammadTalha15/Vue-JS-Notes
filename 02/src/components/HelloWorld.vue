<template>
  <h2>The Count is {{ count }}</h2>
  <button @click="count++">Click Me!</button>
</template>

<script>
import { onMounted, reactive, ref, watch } from 'vue'


export default {
  
  setup() {
    const count = reactive([1, 2, 3]);

    return { count };
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
