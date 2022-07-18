<template>
  <div>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "Hola Vue!"
    }
  }
}
</script>

<style scoped>
p {
  color: red;
}

p:nth-child(2) {
  color: blue;
}
</style>