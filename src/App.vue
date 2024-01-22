<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello world',
      image: 'src/img/b31d57987dbe0b837e8336cec98e18b9.jpg',
      date: '',
    }
  },
  methods: {
    revenge() {
      console.log('V per Vendetta', this.message);
    }
  }
}

</script>

<template>
  <h1>{{ message }}</h1>
  <img :src="image">

  <button @click="revenge">click me</button>

  <input type="text" placeholder="Type a date" v-model="date">
  <div>{{ date }}</div>
</template>

<style></style>
