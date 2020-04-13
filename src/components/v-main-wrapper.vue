<template>
    <div class="v-main-wrapper">
        <h1>{{title}}</h1>
        <keep-alive>
            <router-view></router-view>
        </keep-alive>
    </div>
</template>

<script>
    export default {
        name: 'v-main-wrapper',
        props: {},
        data(){
            return {
                title: 'Magazin'
            }
        },
        computed: {},
        methods: {},
        watch: {},
        }

</script>

<style>
    .v-main-wrapper{
        max-width: 1000px;
        margin: 0 auto;
    }
</style>