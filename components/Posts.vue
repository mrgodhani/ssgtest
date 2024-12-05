<template>
    <div>
        <div v-for="post in posts">
        {{  post.title  }}
      </div>
    </div>
</template>
<script setup lang="ts">
const { data: posts } = useFetch('https://my-json-server.typicode.com/mrgodhani/demo/posts')
</script>