<template>
    <div>
        {{count}}
        <button @click="add">add one</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                count: 0
            }
        },
        methods: {
            add () {
                this.count++
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>