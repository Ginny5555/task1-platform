<template>
  <div class="home">
    <MainView msg />
  </div>
</template>

<script>
import MainView from "@/components/MainView.vue";

export default {
  name: "HomeView",
  components: {
    MainView
  }
};
</script>
