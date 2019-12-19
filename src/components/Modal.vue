<template>
    <div class="modal">
        <div
            class="background"
            @click="$emit('close')"
        ></div>
        <content>
            <slot />
        </content>
    </div>
</template>


<style scoped>
.modal {
    width: 100%;
    height: 100%;
    position: fixed;
    z-index: 1000;
    top: 0;
    left: 0;
}
.background {
    width: 100%;
    height: 100%;
    background: rgba(50, 50, 50, 0.85);
}
content {
    position: absolute;
    background: white;
    height: 508px;
    width: 350px;
    top: 50%;
    margin-top: -254px;
    left: 50%;
    margin-left: -175px;
    /* box-shadow: 2px 2px 15px #999; */
}
</style>