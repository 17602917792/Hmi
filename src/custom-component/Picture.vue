<template>
    <div style="overflow: hidden;">
        <img :src="propValue">
    </div>
</template>

<script>
export default {
    props: {
        propValue: {
            type: String,
            require: true,
            default: '',
        },
        element: {
            type: Object,
            default: () => {},
        },
    },
}
</script>

<style lang="scss" scoped>
img {
    width: 100%;
    height: 100%;
}
</style>
