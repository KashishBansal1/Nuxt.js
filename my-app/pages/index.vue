<template>
  <div>
    <!-- <Tutorial /> -->
    <home />
    <About />
  </div>
</template>

<script>
import About from "../components/About";
import home from "../components/home";
export default {
  name: 'IndexPage',
  components: {
    About,
    home
  },
}
</script>
