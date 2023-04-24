<template>
  <v-app dark>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
};
</script>

<style scoped>
main {
  background-image: linear-gradient(
    to right,
    rgba(6, 227, 76, 0.407),
    rgba(0, 64, 255, 0.374)
  );
}
</style>
