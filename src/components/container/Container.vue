<style>

</style>
<template>
  <div>
    <div style="width:100%;min-height:368px;background:#fff;">
      <div style="width:14%;background:#1C2B36;min-height:368px;float:left;">
        <SiderbarLeft ></SiderbarLeft>
      </div>
      <div style="width:86%;min-height:368px;background:#fff;margin-left:14%;">
        <ContentRight ></ContentRight>
      </div>
    </div>
  </div>
</template>
<script>
  import SiderbarLeft from '@/components/container/SiderbarLeft'
  import ContentRight from '@/components/container/ContentRight'

  export default{
    name: 'container',
    components: {
      SiderbarLeft,
      ContentRight
    }
  }
</script>
