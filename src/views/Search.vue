<!--  -->
<template>
  <div class="search">
    搜索结果
    <hr/>
    {{this.$route.query.searchData}}
  </div>
</template>

<script>
export default {
  name: 'Search',
  data () {
    return {
    }
  },
  mounted(){
      console.log(this.$route.query.searchData)
  }
}
</script>

<style lang='stylus' scoped>

</style>
