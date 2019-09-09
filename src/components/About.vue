<template>
  <div class="about">
    <h1>Hello {{ their_name }}, this is an about page</h1>
    <p>This is Stuti's todo list in vue js.</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>