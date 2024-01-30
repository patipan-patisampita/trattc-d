<template>
    <div>
        <navbar-view />
        <router-view />
        <footer-view />
    </div>
</template>

<script setup>
import NavbarView from './NavbarView.vue';
import FooterView from './FooterView.vue';
</script>

<style lang="scss" scoped></style>