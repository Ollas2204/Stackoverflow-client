<template>
  <div class="home">
    <Question />
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Question from '@/components/Question.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Header,
    Question,
  }
}
</script>
