<template>
  <div class="container m-5">
    <COptionAPI/>
    <hr/>
    <CCompositionAPI/>
  </div>
</template>

<script>
import COptionAPI from "@/components/COptionAPI";
import CCompositionAPI from "@/components/CCompositionAPI";

export default {
  name: 'App',
  components: {
    CCompositionAPI,
    COptionAPI
  }
}
</script>
