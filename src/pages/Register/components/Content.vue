<template>
  <div style="margin: auto">
    <h2>Register your card ID</h2>
    <div class="container">
      <input />
      <button>Register</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  gap: 1rem;
  line-height: 1.6rem;
  font-size: 1.5rem;
  font-weight: bold;
  flex-wrap: wrap;
}
.item {
  cursor: pointer;
  padding: 3rem;
  max-width: 12ch;
  box-shadow: 0px 3px 3px -2px rgb(0 0 0 / 20%),
    0px 3px 4px 0px rgb(0 0 0 / 14%), 0px 1px 8px 0px rgb(0 0 0 / 12%);
}
</style>
