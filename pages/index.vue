<template>

<div class="container">
  <div class="center">
     <img src="/wappen.png" />
  </div>
</div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>

.container {
display: flex;
  justify-content: center;

}

.center {
 margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);

 
}

</style>