<template>
    <div>
        <h2>Testing component {{ name }}</h2>
        <slot>Empty Slot</slot>
    </div>
</template>

<script>
    export default {
        props:['name'],
        name: 'TestCard',
    }
</script>