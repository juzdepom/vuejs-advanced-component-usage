<template>
  <div>
    <div class="italic">
      <slot name="title"></slot>
      <span style="color: #ccc"><slot name="subtitle">Subtitle</slot></span>
    </div>
    <div>
      <slot name="content"></slot>
    </div>
  </div>

</template>

<script>

</script>

<style scoped>
  div {
    text-align: center;
    border: 1px solid #ccc;
    box-shadow: 1px, 1px, 2px, black;
    padding: 30px;
    margin: 30px auto;
  }
  h2 {
    color: red;
  }
  .italic {
    font-style: italic;
  }
</style>
