<template>
  <div class="container">
  <h2>
    Who doesn't love a good Dad Joke?
  </h2>
  <br>
  <hr />
  <br>
  <img src="https://thumbs.dreamstime.com/b/father-little-son-home-sitting-sofa-boy-tickling-dad-laughing-cheerful-together-134197657.jpg" alt="A dad, laughing">
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Welcome to dad jokes',
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

<style scoped>

h2 {

  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  justify-content: center;
}

</style>
