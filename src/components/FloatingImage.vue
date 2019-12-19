<template>
    <div class="floating-image">
        <slot />
    </div>
</template>

<style scoped>
.floating-image {
    position: absolute;
    top: 20%;
    left: 15%;
    width: 25%;
    max-width: 500px;
}
img {
    width: 100%;
}
</style>