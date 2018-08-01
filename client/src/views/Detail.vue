<template>
  <div class="home">
    <Detail />
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Detail from '@/components/Detail.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Detail,
    Header,
  }
}
</script>
