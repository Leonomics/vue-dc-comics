<template>
    <main>
        <div class="mainContainer container">
            <ComicsItem></ComicsItem>
        </div>
    </main>
</template>

<script>
    import ComicsItem from './ComicsItem.vue'
    export default{
    name: "MainItem",
    components: { ComicsItem }
}
</script>

<style scoped lang="scss">
    main{
        color: white;
        background-color: black;
    }
    .mainContainer{
        display: flex;
        align-items: center;
    }
</style>