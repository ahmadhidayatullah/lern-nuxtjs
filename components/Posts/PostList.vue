<template>
  <section class="featured-posts">
    <PostPreview
      id="1"
      thumbnail="https://upload.wikimedia.org/wikipedia/en/thumb/6/62/BBC_News_2019.svg/1200px-BBC_News_2019.svg.png"
      title="hello 1"
      previewText="lorem ipsum"
    />
    <PostPreview
      id="2"
      thumbnail="https://upload.wikimedia.org/wikipedia/en/thumb/6/62/BBC_News_2019.svg/1200px-BBC_News_2019.svg.png"
      title="hello 2"
      previewText="lorem ipsum"
    />
    <PostPreview
      id="3"
      thumbnail="https://upload.wikimedia.org/wikipedia/en/thumb/6/62/BBC_News_2019.svg/1200px-BBC_News_2019.svg.png"
      title="hello 3"
      previewText="lorem ipsum"
    />
  </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";
export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>