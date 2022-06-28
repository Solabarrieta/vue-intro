<template>
<div>
    <p>Lorem ipsum</p>
    <div>{{ text }}</div>
</div>
</template>

<script>
export default {
    data() {
        return {
            text: "Hola"
        };
    }
};
</script>

<style scoped>
p {
    color: turquoise;
}
</style>