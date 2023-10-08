<template>
  <div class="container">
    <h2>Two-Way Binding</h2>
    <input v-model="message" placeholder="Enter a message" />
     <p>Message: {{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "",
    };
  },
};
</script>
