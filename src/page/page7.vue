<template lang="html">
    <div>
        <p>路由传值({{id}})</p>
        <p>参数传值({{param1}}, {{param2}})</p>
        <p>testtest</p>
    </div>
</template>

<script>
export default {
    data () {
         return {
             id: this.$route.params.id,
             param1: this.$route.params.param1,
             param2: this.$route.params.param2,
         }
    }
}
</script>

<style lang="css">
</style>
