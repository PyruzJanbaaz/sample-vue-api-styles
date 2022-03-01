<template>
  <p class="alert alert-info">
    <strong class="d-block">Option API</strong>
    {{ title }}
    <small class="d-block">
      Go with Options API if you are not using build tools, or plan to use Vue primarily in low-complexity scenarios, e.g. progressive enhancement.
    </small>
  </p>
  <button @click="changeTitle" class="btn btn-primary">Call change method!</button>
</template>

<script>
export default {
  name: "COptionAPI",
  data() {
    return {
      title: 'Initialed OptionAPI!'
    }
  },
  mounted() {
    this.title = 'Mounted OptionAPI!';
  },
  methods: {
    changeTitle() {
      this.title = 'Changed OptionAPI!';
    }
  }
}
</script>
