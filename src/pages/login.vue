<template>
<div class="login">
    <div class="filedSet">
        <legend class="legend">登录滚雪球</legend>
        <div class="inputGroup">
            <el-input class="input" placeholder="请输入用户名" v-model="input21"></el-input>
            <el-input class="input" placeholder="请输入密码" v-model="input21" type="password"></el-input>
            <el-button type="primary" plain>登录</el-button>
        </div>
    </div>
</div>
</template>
<script>
export default {
    name: 'Login',
    components: {
  }
}
</script>
<style lang="less" scoped>
.login {
    display: flex;
    justify-content: center;
    margin-top: 250px;
    height: 100%;
    align-items: center;
}
.filedSet {
    height: 250px;
    width: 400px;
    background-color: #fff;
    border-radius: 10px;
    border: 1px solid #f0f0f0;
    .legend{
        box-sizing: border-box;
        color: #fff;
        width: 100%; 
        background: #FF7052;
        padding: 15px;
        font-size: 20px;
    }
    .input {
        padding: 10px;
        margin: 0 auto;
        width: 80%;
    }
}
</style>