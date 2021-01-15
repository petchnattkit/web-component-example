<template>
  <div id="web-component-example">
    <div>
      <p>Insert text here</p>
      <input title="insert text here" aria-placeholder="insert text here" placeholder="insert text here" type="text" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'InputWebComponent'
}
</script>
<style scoped>
p {
  display: inline;
  margin-bottom: 0px;
  margin-top: 0px;
  margin-right: 8px;
}

@media only screen and (max-width: 425px) {
  #web-component-example {
    margin-left: 16px;
    margin-right: 16px;
  }
}

@media only screen and (min-width: 426px) and (max-width: 768px) {
  #web-component-example {
    margin-left: 32px;
    margin-right: 32px;
  }
}

@media only screen and (min-width: 767px) {
  #web-component-example {
    margin-left: 64px;
    margin-right: 64px;
  }
}
</style>
