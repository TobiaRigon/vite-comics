<script>
import ListaComics from './ListaComics.vue'

export default {
    name: "AppMain",

    components: {

        ListaComics,

    },
}
</script>

<template>
    <main>
        <div class="container">
            <ListaComics />
        </div>
    </main>
</template>

<style scoped lang="scss">
@import "../style/partial/variables.scss";



main {

    background-color: $main_gray;

    // debug
    min-height: 200px;
    color: white;
}
</style>