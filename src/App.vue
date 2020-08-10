<template>
    <div class="app" id="app">
        <div class="nav">
            <div class="logo">
                <h2>(Logo)</h2>
            </div>
            <div class="nav">
                <router-link to="/">Home</router-link>|
                <a href="#about">About</a> |
                <a href="#refs">Work With</a> |
                <a href="#contact">Contact</a>
            </div>
        </div>

        <router-view />
    </div>
</template>

<style lang="scss">
@import "./scss/main.scss";
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
</style>