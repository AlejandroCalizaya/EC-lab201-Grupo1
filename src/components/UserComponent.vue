<script>
export default {
  name: "HomeView",
  props: ["displayName", "img", "followers"],
};
</script>

<template>
  <div class="followers">
    <h1>Followers:</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .followers {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
