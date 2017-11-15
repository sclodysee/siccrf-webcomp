<template>
  <div class="test">
    <h1>Hello siccrf-webcomp!</h1>
    <input v-model="name" placeholder="Name" />
  </div>
</template>

<script>
export default {
  name: 'test',

  data () {
    return {
      name: 'Hello from DGCCRF',
    }
  },
}
</script>

<style scoped>
.test h1 {
  color: #40b883;
}
</style>
