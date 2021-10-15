<template>
  <div>
    <input type="text" placeholder="your route" v-model="userId" />
    <button @click="onLoadUser">Request</button>
  </div>
</template>

<script>
export default {
  methods: {
    onLoadUser() {
      this.$router.push("/first/" + this.userId);
    }
  }
};
</script>
