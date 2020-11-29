<template>
  <div class="home">
    <HeaderCp />
    <HomeCp />
    <FooterCp />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeCp from '@/components/HomeCp.vue'
import HeaderCp from '@/components/HeaderCp.vue'
import FooterCp from '@/components/FooterCp.vue'

export default {
  name: 'Home',
  components: {
    HomeCp,
    HeaderCp,
    FooterCp
  }
}
</script>
