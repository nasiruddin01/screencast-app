<template>
  <div style="max-width:100vw;text-align: center;display: flex; flex-direction: column;justify-content:center;align-item:center;">
    <h1 style="margin:5rem 0rem 3rem 0rem;">Editing {{ video.name }}</h1>
    <nuxt-link :to="`/videos/${video.id}`">
      <button style="">
        Go back to show
      </button>
    </nuxt-link>
  </div>
</template>

<script>
export default {
  props: ["video"],
};
</script>

<style lang="scss" scoped>
</style>