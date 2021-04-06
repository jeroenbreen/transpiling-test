<script>
    import Flex from "./components/Flex";
    export default {
        name: 'App',
        components: {Flex}
    }
</script>


<template>
    <div class="app">
        <h1>
            Test app to see what transpiling does
        </h1>
        <Flex/>
    </div>
</template>


<style lang="scss">
    .app {

        h1 {

        }

        .example {

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
