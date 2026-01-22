<template>
  <div> class="Durian">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Durian and mangosteen',
      message: 'I Love Durian and mangosteen'
    }
  }
};
</script>

<style>
  .Durian {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb (207, 222, 56);
  }
</style>