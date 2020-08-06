<template>
    <div>
        <h1>My Error Page</h1>
        <div v-if="error.statusCode === 404">
            Error 404 Page Not Found!
        </div>
        <div v-else>
            Generic Error
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            error: {
                type: Object
            },
        },
    }
</script>

<style lang="scss" scoped>

</style>