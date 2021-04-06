<script>
    export default {
        name: 'Flex',
        components: {},
        computed: {},
        methods: {}
    }
</script>


<template>
    <div class="Flex example">
        <div class="example__head">
            1) CSS: Flex
        </div>
        <div class="example__body">
            <div class="flex-container">
                <div class="flex-element">1</div>
                <div class="flex-element">2</div>
                <div class="flex-element">3</div>
            </div>
        </div>
    </div>
</template>


<style lang="scss">
    .Flex {

        .flex-container {
            display: flex;

            .flex-element {
                flex-grow: 1;
                background: #ddd;
                border: 1px solid #fff;
                display: flex;
                justify-content: center;
                height: 32px;
                align-items: center;
            }
        }
    }
</style>
