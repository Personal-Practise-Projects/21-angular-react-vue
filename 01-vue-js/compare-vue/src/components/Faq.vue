<template>
  <section class="faq">
    <div class="container">
      <div class="row">
        <div class="col-12">
          FAQ Page
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'faq'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

@import '../mq';

h1, h2 {
  font-weight: normal;
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
