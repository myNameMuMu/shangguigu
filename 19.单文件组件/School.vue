<template>
    <div>
        <div>学校名称：{{name}}</div>
        <div>地址：{{address}}</div>
    </div>
</template>

<script>
    export default Vue.exrend({
        data() {
            return {
                name: '尚硅谷',
                address: '北京顺义'
            }
        }
    })
</script>

<style>

</style>