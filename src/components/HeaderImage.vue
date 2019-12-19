<template>
    <div
        class="full-width-image"
        :style="`max-height: ${maxHeight}px`"
    >
        <slot />
        <div
            v-if="overlay"
            class="full-width-image--overlay"
        ></div>
    </div>
</template>

<script>
export default {
  props: {
    overlay: {
      type: Boolean,
      default: false
    },
    maxHeight: {
      type: Number,
      default: 1000
    }
  }
}
</script>

<style scoped>
.full-width-image {
    width: 100%;
    max-height: 500px;
    overflow: hidden;
    display: flex;
    align-items: center;
    position: relative;
}
.full-width-image--overlay {
    height: 100%;
    width: 100%;
    opacity: 0.25;
    background: black;
    position: absolute;
}
img {
    width: 100%;
}
</style>
