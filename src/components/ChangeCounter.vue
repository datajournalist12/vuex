<template>
    <button @click="addOne">Add 1</button>
</template>

<script lang="ts">
export default {
    methods: {
        addOne() {
            this.$store.commit('increment');
        }
    }
}
</script>
