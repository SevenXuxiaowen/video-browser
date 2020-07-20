<template>
    <div>
        <input type="text" @input="termChange">
    </div>
</template>

<script>
export default {
    name: 'SearchBar',
    methods:{
        termChange(e){
            this.$emit("onTermChange", e.target.value)
        }
    }
}
</script>

<style >

</style>