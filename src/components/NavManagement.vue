<!--管理页面 - 导航栏-->
<template>
    <nav class="navbar navbar-expand-md navbar-light bg-light">
        <a class="navbar-brand my-2 my-lg-0" href="#">Gjy's blogo</a>
        <!--       导航栏折叠后的 折叠按钮-->
        <button class="navbar-toggler" type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <!--宽度不够厚会被折叠的部分-->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">

            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="form-control btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "NavManagement"
    }
</script>

<style scoped>

</style>