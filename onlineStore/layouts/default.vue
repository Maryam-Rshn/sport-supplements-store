<template>
    <div>
        <header></header>

        <div>
            <slot />
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss">
@import "~/assets/scss/global.scss";

.router-link-exact-active {
    color: aqua;
}

</style>