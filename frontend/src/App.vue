<script setup>
import Navbar from './components/Navbar.vue'
import { RouterView } from 'vue-router'

</script>

<template>
    <Navbar />
    <div class="container m-4">
        <RouterView />
    </div>
</template>