<template>
    <div class="app-layout">
        <header class="header">
            <div>
                <img class="img" src="../assets/logo.svg"/>
                <div> Centrum wsparcia firmy XYZ </div>
            </div>
        </header>

        <router-vue />
    </div>
</template>

<style lang="stylus">
@import '../style/main';
</style>

<style lang="stylus" scoped>
.header {
    .img {
        width: 64px;
        height: 64px;
    }
}
</style>