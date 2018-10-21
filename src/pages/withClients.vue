<template>
  <div id="withClients">
    
  </div>
</template>

<script>
import { mapGetters, mapActions } from 'vuex'
import EditModal from './../components/ownComponent/withClients/editModal'
import ClientsSearch from './../components/ownComponent/withClients/ClientsSearch'

export default {
  name: 'withClients',
  components: {
    EditModal,
    ClientsSearch
  },
  computed: {
    ...mapGetters([])
  },
  methods: {
    ...mapActions([])
  },
  mounted () {
    
  },
  data () {
    return {
      
    }
  }
}
</script>

<style lang="less" scoped>
#withClients {
  
}
</style>
