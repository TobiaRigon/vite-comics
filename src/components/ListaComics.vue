<script>
import ComicsCard from './ComicsCard.vue'


export default {
    name: "ListaComics",

    components: {

        ComicsCard,

    },
}
</script>

<template>
    <ComicsCard />
</template>

<style scoped lang="scss">
@import "../style/partial/_variables.scss";
</style>