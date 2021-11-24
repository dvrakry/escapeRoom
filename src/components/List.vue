<template>
  <div>
      <h5> {{roomInfo[0].title}} </h5>
      <p> {{roomInfo[0].content}} </p>
      <p>{{roomInfo[0].date}}</p>
  </div>
</template>

<script>
export default {
    name : 'list',
    props : {
        roomInfo : Array,
    }
}
</script>

<style>

</style>