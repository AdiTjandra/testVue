<style scoped>

h1,
h2 {
    font-weight: normal;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}

</style>

<template>

<div class="hello">
    <h1>{{ msg }}</h1>

</div>

</template>

<script>

export default {
    name: 'HelloWorld',
    data() {
        return {
            msg: 'Welcome to The Secret Shop'
        }
    }
}

</script>
