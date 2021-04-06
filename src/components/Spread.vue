<script>
export default {
    name: 'Spread',
    components: {},
    data() {
        return {
            arr: ['Amsterdam', 'Warsaw', 'Kopenhagen', 'Riga']
        }
    },
    computed: {
        spread(){
            return [...this.arr].join(' + ');
        }
    },
    methods: {}
}
</script>


<template>
    <div class="Spread example">
        <div class="example__head">
            2) Array spread (...)
        </div>
        <div class="example__body">
            {{spread}}
        </div>
    </div>
</template>


<style lang="scss">
.Spread {

}
</style>
