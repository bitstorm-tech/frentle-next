<template>
    <div id="frentle-module">
        Frentle Module
    </div>
</template>

<script>
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class FrentleModule extends Vue {
    }
</script>

<style scoped>
#frentle-module {
    width: 100%;
    background-color: #42b983;
    height: 250px;
}
</style>
