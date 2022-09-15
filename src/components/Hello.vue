<template>
    <div>
        <h1>Hello, 你好，{{ name }}</h1>
        <el-switch v-model="value" active-color="#13ce66" inactive-color="#ff4949">
        </el-switch>
    </div>
</template>

<script>

export default {
    data() {
        return {
            name: '张三',
            value: true
        }
    }
}
</script>

<style>
</style>
