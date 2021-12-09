<template>
  <div style="margin: auto">
    <h2>Parking Spots</h2>
    <div class="container">
      <div class="item" v-for="option in options" :key="option.id">
        {{ option.id }}, {{ option.label }}, {{ option.timestamp }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content",
  data() {
    return {
      options: [
        { label: "spot1", id: "155dsd", timestamp: "0000000" },
        { label: "spot1" },
        { label: "spot1" },
        { label: "spot1" },
        { label: "spot1" },
        { label: "spot1" },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  gap: 2rem;
  line-height: 1.6rem;
  font-size: 1.5rem;
  font-weight: bold;
  flex-wrap: wrap;
  justify-content: center;
  max-width: 600px;
}
.item {
  cursor: pointer;
  padding: 3rem;
  max-width: 12ch;
  box-shadow: 0px 3px 3px -2px rgb(0 0 0 / 20%),
    0px 3px 4px 0px rgb(0 0 0 / 14%), 0px 1px 8px 0px rgb(0 0 0 / 12%);
}
</style>
