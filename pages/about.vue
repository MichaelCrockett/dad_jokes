<template lang="html">
  <div class="">
    <h1>About this app</h1>
    <p>This is an app that has a searchable database of some tremendous Dad Jokes</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'About The App',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Best place for corny dad jokes'
        }
      ]
    };
  }
};
</script>

<style lang="css" scoped>
</style>
