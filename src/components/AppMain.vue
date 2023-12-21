<script>
export default {
    name: "AppMain",
}
</script>

<template>
    <main>
        <div class="container">
            ciao main
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