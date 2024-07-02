<template>
  <div></div>
</template>

<script scoped>
console.log("in");

export default {
  async asyncData({ redirect }) {
    redirect("/index");
  },
};
</script>
