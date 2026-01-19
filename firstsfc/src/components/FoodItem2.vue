<template>
  <div class="pineapple">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Mango and Strawberry',
      message: 'I like pineapple'
    }
  }
};
</script>

<style>
  .pineapple {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: yellow;
  }

</style>