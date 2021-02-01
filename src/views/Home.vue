<template>
    <div class="home">
        home
        home
        home
        home
        home
        home
        <el-button @click="user">跳转</el-button>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    } ,
    methods : {
        user() {
            this.$router.push('/user')
        }
    }
}
</script>

<style>

</style>