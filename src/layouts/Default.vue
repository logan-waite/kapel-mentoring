<template>
    <div class="layout">
        <!-- <Navbar></Navbar> -->
        <div class='content'>
            <slot />
        </div>
    </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>

<style>
body {
    font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI",
        Roboto, "Helvetica Neue", Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.5;
    background: whitesmoke;
}
.layout {
    max-width: 1500px;
    margin: auto;
    background-color: white;
}
</style>
