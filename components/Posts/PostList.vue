<template lang="pug">
    section.post-list
      PostPreview(id="1" title="First Post" thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg" previewText="This is my first post")
      PostPreview(id="2" title="Second Post" thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg" previewText="This is my second post")
      PostPreview(id="3" title="Third Post" thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg" previewText="This is my third post")</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
  components: {
    PostPreview
  }
}
</script>

<style>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>