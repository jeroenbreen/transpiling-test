<script>
    import Flex from "./components/Flex";
    import Spread from "./components/Spread";
    export default {
        name: 'App',
        components: {Spread, Flex}
    }
</script>


<template>
    <div class="app">
        <h1>
            Test app to see what transpiling does
        </h1>
        <Flex/>
        <Spread/>
    </div>
</template>


<style lang="scss">
    .app {

        h1 {

        }

        .example {
            margin-bottom: 32px;

            .example__head {
                font-weight: 700;
                border-left: 2px solid red;
                padding-left: 8px;
                margin-bottom: 12px;
            }

            .example__body {
                border: 1px solid #ddd;
                padding: 8px;
            }
        }
    }
</style>
