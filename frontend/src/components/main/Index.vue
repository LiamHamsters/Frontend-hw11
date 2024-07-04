<!--WORKING-->
<template>
  <div>
    iii
    <Post v-for="post in posts" :post="post" :key="post.id" />
  </div>
</template>

<script>
import Post from "@/components/page/Post.vue";

export default {
  name: "Index",
  components: {Post},
  props: ["posts"]
}
</script>

<style scoped>

</style>