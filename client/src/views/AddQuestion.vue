<template>
  <div class="home">
    <Header />
    <AddQuestion />
  </div>
</template>

<script>
// @ is an alias to /src
import AddQuestion from '@/components/AddQuestion.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Header,
    AddQuestion,
  }
}
</script>
