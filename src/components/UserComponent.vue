<script>
export default {
  name: "HomeView",
  props: ["displayName", "img", "followers"],
};
</script>

<template>
  <h2>{{ displayName }}</h2>
  <img :src="img" />
  <h2>Followers: {{ followers.total }}</h2>
</template>
