<template>
  <div class="education">
    <h1 style="color: lightpink">{{ message }}</h1>
    <p>{{ msg }}</p>
    <p>{{ msg2 }}</p>
    <p>{{ msg3 }}</p>

    <hr class="style1" />
  </div>
</template>

<script>
export default {
  name: 'Education',
  data() {
    return {
      message: 'Education',
      msg: 'Elementary: Dee Hwa Liong College Foundation',
      msg2: 'JHS-SHS: Angeles University Foundation - Integrated School',
      msg3: 'College: Holy Angel University',
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
