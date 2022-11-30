<template>
    <h1>Hello {{ name }}</h1>
    <p>In this tutorial we will use the series frameworks</p>

    <Nav />
</template>

<script>
import Nav from '../Shared/Nav.vue';

export default {
    components: { Nav },
}
</script>
