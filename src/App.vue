<template>
  <div id="material-kit">
    <div :class="{ 'nav-open': NavbarStore.showNavbar }">
      <router-view name="header" />
      <div>
        <router-view />
      </div>
      <router-view name="footer" />
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      list: [],
    };
  },
};
</script>
