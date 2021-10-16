<template>
  <div>
    <input type="text" placeholder="your route" v-model="userId" />
    <button @click="onLoadUser">Request</button>
    <nuxt-child />
  </div>
</template>

<script>
export default {
  data() {
    return { userId: "" };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/first/" + this.userId);
    }
  }
};
</script>
