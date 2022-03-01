<script setup>
import {ref, onMounted} from 'vue'

const title = ref('Initialed OptionAPI!');

onMounted(() => {
  title.value = 'Mounted OptionAPI!';
})

function changeTitle() {
  title.value = 'Changed OptionAPI!';
}
</script>


<template>
  <p class="alert alert-warning">
    <strong class="d-block">Composition API</strong>
    {{ title }}
    <small class="d-block">
      Go with Composition API + Single-File Components if you plan to build full applications with Vue.
    </small>
  </p>
  <button @click="changeTitle" class="btn btn-warning float-end">Call change method!</button>
</template>
