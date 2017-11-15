<template>
  <div>
    <h1>Je suis le composant &lt;test&gt;&lt;/test></h1>
    <input v-model="name" placeholder="Name" />
  </div>
</template>

<script>
export default {
  name: 'test',

  data () {
    return {
      name: 'Hello World',
    }
  },
}
</script>

<style>
 h1 {
  color: #40b883;
}
</style>
