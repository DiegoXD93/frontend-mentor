<template>
  <div class="home">
    <Index msg="Front-End Mentor" />
  </div>
</template>

<script>
// @ is an alias to /src
import Index from '@/components/Index.vue'

export default {
  name: 'Home',
  components: {
    Index
  }
}
</script>
