<template lang="jade">
.container(style="padding: 20px")
  .btn.btn-floating
    icon(name="material-cancel")
  p
    a(href="https://github.com/paulpflug/vue-materialize/blob/master/dev/icon.vue") source
</template>

<script lang="coffee">
module.exports =
  components:
    "icon" : require "../src/icon.coffee"

</script>
