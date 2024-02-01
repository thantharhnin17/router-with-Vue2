<template>
    <div>
        <NavBar />
        <h1>Home Page</h1>
    </div>
</template>

<script>
    import NavBar from './NavBar.vue'

    export default {
        name: 'HomePage',
        components: {
            NavBar,
        }
    }
</script>