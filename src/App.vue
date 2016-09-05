<template>
  <div>
    <button @click="clicked">
      Click to
      <template v-if="!hide">
        hide
      </template>
      <template v-else>
        show
      </template>
    </button>
    <h1 v-if="!hide">{{ msg }}</h1>
  </div>
</template>

<script>
export default {

  data () {
    return {
      msg: 'Hello Vue!',
      hide: false
    }
  },

  methods: {
    clicked () {
      this.hide = !this.hide
    }
  }

}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
