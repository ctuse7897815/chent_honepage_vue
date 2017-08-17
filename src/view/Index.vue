<style>

</style>
<template>
  <div>
    <Top />
    <Container/>
  </div>
</template>
<script>
  import Top from '@/components/navbar/NavbarTop'
  import Container from '@/components/container/Container'

  export default{
    name: 'index',
    components: {
      Top,
      Container
    },
    data () {
      return {
        msg: '123'
      }
    }
  }
</script>
