<template lang="pug">
.hello
  h1 Nuclear Subtitution Vue
  h2 When Boomers Rang
  h3  
  button.btn.btn-lg.btn-default.btn-icon-label(type='button')
    span.btn-inner--icon
      i.fas.fa-sun
    span.btn-inner--text(style="margin-right: 12px") Imprints
  button.btn.btn-lg.btn-dark.btn-icon-label(type='button')
    span.btn-inner--icon
      i.fas.fa-sun
    span.btn-inner--text Offprints
  button.btn.btn-lg.btn-danger.btn-icon-label(type='button')
    span.btn-inner--icon
      i.fas.fa-sun
    span.btn-inner--text Footprints
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
