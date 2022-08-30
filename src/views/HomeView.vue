<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <VolunteerOpp msg="Welcome to Your Vue.js App" />
    <FeedOpp />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import VolunteerOpp from "@/components/VolunteerOpp.vue";
import FeedOpp from "@/components/FeedOpp.vue";

export default {
  name: "HomeView",
  components: {
    VolunteerOpp,
    FeedOpp,
  },
};
</script>
