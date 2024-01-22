<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello world',
      image: 'src/img/b31d57987dbe0b837e8336cec98e18b9.jpg',
    }
  }
}

</script>

<template>
  <h1>{{ message }}</h1>
  <img :src="image">
</template>

<style></style>
