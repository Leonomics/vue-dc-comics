<template>
    <main>
        <div class="container">
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
        height: 130px;
    }
</style>