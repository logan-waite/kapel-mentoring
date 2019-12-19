<template>
    <div
        class="text-with-background-image"
        :style="`width: ${width}px; height: ${height}px`"
    >
        <div class="background">
            <slot name="image" />
        </div>
        <div class="content">
            <slot />
        </div>
    </div>
</template>

<script>
export default {
  props: {
    image: {
      type: String,
      required: true
    },
    width: {
      type: Number,
      default: 200
    },
    height: {
      type: Number,
      default: 200
    }
  }
}
</script>
<style scoped>
.text-with-background-image {
    position: relative;
}
.content {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    color: white;
}

.background {
    overflow: hidden;
    width: 100%;
    height: 100%;
    background-color: black;
}
img {
    height: 100%;
    opacity: 0.85;
}
</style>