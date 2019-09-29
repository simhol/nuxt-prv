<template lang="pug">
  .admin-page
    section.new-post
      button Create Post
    section.existing-post
      h1 Exisiting Posts
      PostList  
</template>

<script>
import PostList from '@/components/Posts/PostList'
export default {
  components: {
    PostList
  }
}
</script>

<style scoped>
.admin-page {
  padding: 20px;
}

.new-post {
  text-align: center;
  border-bottom: 2px solid #ccc;
  padding-bottom: 10px;
}

.existing-posts h1 {
  text-align: center;
}
</style>