<template>
  <div class="skills">
    <h1 style="color: lightpink">{{ message }}</h1>
    <p>{{ msg2 }}</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      message: 'Skills',
      msg2: 'Creating and designing website using HTML and CSS',
    };
  },
};
</script>

<style scoped>
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
  color: lightpink;
}
</style>
