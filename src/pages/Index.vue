<template>
  <HomeLayout>

    homepage dawg

    <div v-for="(post, index) in $static.posts.edges">
      {{ post }}
    </div>

    <img src="/uploads/screen-shot-2020-07-22-at-10.17.49-pm.png" />

  </HomeLayout>
</template>

<script>
import HomeLayout from '@/layouts/Home.vue'

export default {
  metaInfo: {
    title: 'Hello, world!'
  },
  components: {
    HomeLayout
  }
}
</script>

<static-query>
query {
  posts: allPost {
    edges {
      node {
        id
        title
        excerpt
      }
    }
  }

}
</static-query>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
