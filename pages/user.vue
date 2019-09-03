<template>
  <div>
    <input type="text" v-model="userID" />
    <button @click="onLoadUser">Load Data</button>
    <nuxt-child />
  </div>
</template>
<script>
export default {
  data() {
    return {
      userID: ""
    };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/user/" + this.userID);
    }
  },
  layout: "user"
};
</script>