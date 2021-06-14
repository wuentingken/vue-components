<template>
    <div>
        <Button @click="this.add">按钮</Button>
    </div>
</template>
<script>

export default{
    data() {
        return {
            count: 1
        }
    },
    methods: {
        add() {
            this.count++
        }
    }
}
</script>
