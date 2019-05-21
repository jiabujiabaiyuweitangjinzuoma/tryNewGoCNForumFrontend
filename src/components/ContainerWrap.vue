<template>
    <div id="container-wrap" class="container">

        <div>
            <b-tabs content-class="mt-3">
                <b-tab title="最新" active><p>I'm the first tab</p></b-tab>
                <b-tab title="推荐"><p>I'm the second tab</p></b-tab>
                <b-tab title="热门"><p>I'm a disabled tab!</p></b-tab>
                <b-tab title="等待回复"><p>I'm a disabled tab!</p></b-tab>
            </b-tabs>
        </div>

    </div>
    
</template>

<script>
    export default {
        name: "ContainerWrap"
    }
</script>

<style scoped>

    #container-wrap{
        margin-top: 20px;
    }

</style>