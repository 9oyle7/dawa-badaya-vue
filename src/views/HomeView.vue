<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
  </div>
  <ButtonComponent text="اضغط هنا" />
</template>

<script>
import ButtonComponent from "@/components/ButtonComponent.vue";

// @ is an alias to /src

export default {
  name: "HomeView",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    ButtonComponent,
  },
};
</script>
