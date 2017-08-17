<style>

</style>
<template>
  <div >
    <ul>
      <li v-for="item in list">
        <div>

        </div>
      </li>
    </ul>
  </div>
</template>
<script>
export default{
  name: 'siderbar-left',
  props: {
    list: Array
  }
}

</script>
