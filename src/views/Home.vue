<template>
    <div class="home">
            home
    </div>
</template>

<script>
    // @ is an alias to /src
    export default {
        name: 'home',
        data: function () {
            return {
                list: []
            }
        },
        mounted: function () {
           // this.getList();
        },
        methods: {
        }
    }
</script>
<style lang="scss" scoped>
    .home{
        height: rem(100);
        color: $color;
    }
</style>
