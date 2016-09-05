<template>
  <div>
    <h1>{{ msg }}</h1>
    <p>something</p>
    <button @click="clicked">Click</button>
  </div>
</template>

<script>
export default {

  data () {
    return {
      msg: 'Hello Vue!'
    }
  },

  methods: {
    clicked () {
      alert(this.msg)
    }
  }

}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
