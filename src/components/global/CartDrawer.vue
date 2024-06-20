<template>
  <div class="drawer">
    <v-navigation-drawer location="right" temporary v-model="drawer">
      <v-list :items="items"></v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  name: "CartDrawer",
  inject: ["Emitter"],
  data() {
    return {
      drawer: false,
      items: ["Home", "About", "Contact"],
    };
  },
  mounted() {
    this.Emitter.on("openCart", () => {
      this.drawer = true;
    });
  },
};
</script>
