<template>
  <div>
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import HeaderFile from './Header.vue'
import FooterFile from './Footer.vue'
import BodyFile from './Body.vue'

export default {
  components:{
    'page-header':HeaderFile,
    'page-footer':FooterFile,
    'page-body':BodyFile
  },
  data () {
    return {
    }
  }

}
</script>

<style>

</style>
