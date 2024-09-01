<template>
  <div>
    <button :style="{ color: color, background: background }">
      {{ text }}
    </button>
  </div>
</template>

<script>
export default {
  name: "ButtonComponent",
  props: {
    text: { type: String, Required: true },
    color: { type: String },
    background: { type: String },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button {
  color: #1c9ebe;
  background-color: #e4e4e4;
  border: 0;
  padding: 6px 12px;
  border-radius: 5px;
  font-weight: 700;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}
button:hover {
  color: #1c9ebe;
  background-color: #c9c9c9;
  border: 0;
}
</style>
