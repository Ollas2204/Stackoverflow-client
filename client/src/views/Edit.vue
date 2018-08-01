<template>
  <div class="home">
    <Header />
    <Edit />
  </div>
</template>

<script>
// @ is an alias to /src
import Edit from '@/components/Edit.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Header,
    Edit,
  }
}
</script>
