<style>

</style>
<template>
  <div >
    <div style="height:60px;background:#f0f0f0;padding-left:50px;">
      <img src="./img/logo.png" width="50px" height="50px" style="margin-top:5px;float:left;"/>
      <div style="size:30px;line-height:60px;float:left;margin-left:15px;">{{ title }}</div>
    </div>
  </div>
</template>
<script>
  export default{
    name: 'top',
    data () {
      return {
        title: 'CHENT'
      }
    }
  }
</script>
