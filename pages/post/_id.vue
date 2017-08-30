<template>
  <div>
    <p>{{post.title}}</p>
  </div>
</template>

<script>
  export default {
    async asyncData ({ payload }) {
      return { post: payload }
    }
  }
</script>
