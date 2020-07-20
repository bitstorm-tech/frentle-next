<template>
    <div>
        <button @click="toggle">FrentleButton</button>
        <p>{{visible}}</p>
        <slot v-if="visible"></slot>
    </div>
</template>

<script>
    import {Component, Vue} from 'vue-property-decorator';

    @Component
    export default class FrentleButton extends Vue {
        visible = true;

        toggle() {
            this.visible = !this.visible
        }
    }
</script>

<style scoped>

</style>
