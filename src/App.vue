<template>
    <div id="app">
        <FrentleButton>
            <FrentleModule></FrentleModule>
        </FrentleButton>
    </div>
</template>

<script lang="ts">
    import {Component, Vue} from 'vue-property-decorator';
    import FrentleButton from './components/FrentleButton.vue';
    import FrentleModule from './components/FrentleModule.vue';

    @Component({
        components: {
            FrentleButton,
            FrentleModule
        },
    })
    export default class App extends Vue {
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 20px;
    }
</style>
