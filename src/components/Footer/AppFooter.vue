<template>
  <div>
    <footer>
      <p1>@footer</p1>
      <br>
      <hr>
      <p1>{{msg}}</p1>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
  data () {
    return {
      msg:"welcome!"
    }
  },
  methods: {},
}
</script>

<style scoped>
</style>
