<template>
    <div id="app">
        <img alt="Vue logo" id="im" src="./assets/tedx.png" width="200" />

        <img alt="Vue logo" src="./assets/QR.png" width="300" height="300" />

        <HelloWorld
            id="spacing"
            msg="Welcome to TEDxRUPP,This is your TEDxRUPP Circle ticket.
    Please show this to redeem yourself into the event."
        />
    </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
    name: "App",
    components: {
        HelloWorld,
    },
};
</script>

<style>
body {
    margin: 0;
}

#im {
    text-align-last: center;
}
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    line-height: 12px;
    align-content: center;

    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
}
#spacing {
    line-height: normal;
    align-content: center;
}
</style>
