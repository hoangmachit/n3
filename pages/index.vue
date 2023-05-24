<script>
export default {
  setup() {
    useHead({
      titleTemplate: "useHead example",
      bodyAttrs: {
        class: "home",
      },
    });
    return { dynamic: ref(49) };
  },
  head: {
    title: "Another title",
  },
};
</script>
<template>
  <div>
    <h1>Index Page</h1>
    <nuxt-link to="auth/login">Login Page</nuxt-link>
  </div>
</template>
