<template>
    <h3>{{ example.text }} </h3>
</template>

<script>
    export default{
        name: 'Example',
        props:{
            example: Object,
        },
    }
</script>
