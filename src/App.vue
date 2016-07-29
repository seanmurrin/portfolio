<template>
    <div id="app">
        <img class="logo" src="./assets/logo.png">
        <h1>Coming Soon!</h1>
    </div>
</template>


<style>
html {
    height: 100%;
}

body {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
    background: url('/static/img/wavecrashing.jpg') no-repeat;
    background-size: cover;
}

#app {
    color: #2c3e50;
    margin-top: -100px;
    max-width: 100%;
    font-family: Source Sans Pro, Helvetica, sans-serif;
    text-align: center;
}

#app a {
    color: #42b983;
    text-decoration: none;
}

.logo {
    width: 400px;
    max-width: 90%;
}
</style>
