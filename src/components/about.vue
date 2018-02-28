<template>
  <div class="about">
    <h1>Hello {{  their_name }}, this is an about page</h1> <!-- NOTE! the about page url needs "/name"-string in the end for this to show when using their_name -->
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
  </div>
</template>

<script>
export default {
  name: 'tasks',
  data() {
    return {
        their_name: this.$route.params.name
    }
  }
}
</script>