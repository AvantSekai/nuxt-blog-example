<template>
  <section class="posts-lists">
    <PostPreview
      id="1"
      thumbnail="https://code.visualstudio.com/assets/docs/editor/integrated-terminal/integrated-terminal.png"
      title="Hello there!"
      previewText="This is my first post!"
    />
    <PostPreview
      id="2"
      thumbnail="https://code.visualstudio.com/assets/docs/editor/integrated-terminal/integrated-terminal.png"
      title="Post 2!"
      previewText="This is my second post!"
    />
    <PostPreview
      id="3"
      thumbnail="https://code.visualstudio.com/assets/docs/editor/integrated-terminal/integrated-terminal.png"
      title="Hi on 3!"
      previewText="This is my third post!"
    />
  </section>
</template>

<script>
  import PostPreview from "@/components/Posts/PostPreview";

  export default {
    components: {
      PostPreview,
    },
  };
</script>

<style scoped>
.posts-lists {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>