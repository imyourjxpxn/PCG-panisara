<template >
    <div>
        <button @click="count++">Add 1</button>
        <div>Count is : {{count}}</div>
        <button @click="dropdown=!dropdown">Menu</button>
        <div v-if="dropdown">
            this is dropdown
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            count: 0,
            dropdown: False
        }
    }
}
</script>
<style lang="">
    
</style>
