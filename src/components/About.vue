<template>
  <div class="about">
      <h1>Hello {{user_name}}, This is an about page</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo libero sunt repudiandae quis quos quam doloremque tenetur, in assumenda dolore et voluptate placeat, fuga cum officia laudantium eos excepturi aperiam?</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      user_name: this.$route.params.name
    }
  }
}
</script>
