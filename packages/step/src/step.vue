<template>
    <div>
        <div>{{count}}</div>
        <Button @click="this.add">下一步</Button>
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
