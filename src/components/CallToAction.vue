<template>
    <a
        class="call-to-action"
        :href="target"
        target="_blank"
    >
        <slot />
    </a>
</template>

<script>
export default {
    props: {
        target: {
            type: String,
            default: '#'
        }
    },
}
</script>
<style scoped>
.call-to-action {
    padding: 1rem 1.5rem;
    /* border: 1px solid blue; */
    font-size: 24px;
    background-color: green;
    color: white;
    margin-top: 15px;
    text-align: center;
    text-decoration: none;
}
</style>
