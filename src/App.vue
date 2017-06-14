<template>
    <div id="app">
        <container></container>
    </div>
</template>

<script>
    import container from './components/container';

    export default {
        name: 'app',
        components: {
            container
        }
    };
</script>

<style lang="scss">
    html, body {
        padding: 0;
        margin: 0;
        line-height: 1;
    }
    @font-face {
        font-family: yuanti;
        src: url(/static/yuanti.ttf);
    }
    #app {
        font-family: yuanti;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #333;
    }
</style>
