<template>
  <ons-page>
    <ons-toolbar>
      <div class="center">Onsen UI</div>
    </ons-toolbar>

    <p style="text-align: center">
      <ons-button
        @click="$notification.alert(msg)"
      >
        Click me!
      </ons-button>
    </p>
  </ons-page>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello Vue!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
