<template>

  <div v-for="(post,i) in blog" v-bind:key="i">
    <h5>{{post.title}}</h5>
    <p>{{post.content}}</p>
    <p>{{post.date}}</p>
  </div>
  
  
</template>

<script>

export default {
  name : 'blog',
  props : {
    blog : Array,
  }
}
</script>

<style>

</style>