<template>
    <div>
        <div id="iteration-2">
            <p>Operación matemática: {{2 + 2}}</p>

            <p v-text="printString()"></p>
        </div>

        <div id="iteration-3">
            <p>My favorite serie is: </p>
            <p v-if="favSerie === true">Mr Robot is my favorite serie!</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'basicExercises',
    data() {
        return {
            property: "Hello world!",
            favSerie: true,
        }
    },

    methods: {
        printString() {
            return this.property;
        },
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
