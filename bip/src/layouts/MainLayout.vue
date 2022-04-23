<template>
  <div class="app-main-layout">

    <NavBar />
    <SideBar />

    <main class="app-content">
      <div class="app-page">
        <router-view />
      </div>
    </main>

  </div>
</template>

<script>
import NavBar from "@/components/app/NavBar";
import SideBar from "@/components/app/SideBar";

export default {
  name: "main-layout",
  components: {
    NavBar,
    SideBar,
  },
};
</script>