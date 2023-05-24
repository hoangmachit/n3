<script>
export default {
  setup() {
    useHead({
      titleTemplate: "Auth login",
      bodyAttrs: {
        class: "login",
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
    <h1>Login Page</h1>
  </div>
</template>
