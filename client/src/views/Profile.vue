<template>
  <div class="home">
    <Profile />
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Profile from '@/components/Profile.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Header,
    Profile,
  }
}
</script>
