<template>
  <TheHeader/>
  <TheHome/>
  <TheFooter/>
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import TheHome from "@/components/TheHome.vue";
import TheFooter from "@/components/TheFooter.vue";

export default {
  name: 'App',
  components: {
    TheHeader, TheHome, TheFooter
  }
}
</script>

<style>

</style>
