<template>
  <body>
    <div class="profile">
      <h2 style="color: lightpink">{{ message }}</h2>
      <p>
        {{ msg }}
      </p>

      <p>
        {{ msg2 }}
      </p>
      <p>
        {{ msg3 }}
      </p>
      <p>
        {{ msg4 }}
      </p>
      <p>
        {{ msg5 }}
      </p>
      <hr class="style1" />
    </div>
  </body>
</template>

<script>
export default {
  name: 'Profile',
  data() {
    return {
      message: 'Personal Information',
      msg: 'Name: Cheena Maxine G. Silva',
      msg2: 'Age: 20',
      msg3: 'Email: cgsilva@student.hau.edu.ph',
      msg4: ' Contact Number: +63 935 777 0351',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
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
