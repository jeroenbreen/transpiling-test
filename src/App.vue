<script>
    import Flex from "./components/Flex";
    import Spread from "./components/Spread";
    import Sticky from "./components/Sticky";
    export default {
        name: 'App',
        components: {Sticky, Spread, Flex}
    }
</script>


<template>
    <div class="app">
        <h1>
            Test app to see what transpiling does
        </h1>
        <Flex/>
        <Spread/>
        <Sticky/>
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

            .example__caniuse {
                margin-bottom: 12px;
            }

            .example__body {
                border: 1px solid #ddd;
                padding: 8px;
            }
        }
    }
</style>
