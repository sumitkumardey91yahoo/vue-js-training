<template>
  <div> 
    <parent-com></parent-com>
  </div>
</template>

<script>
import parent from './components/photoCom/parent.vue'

export default {
  data() {
    return {
     
    }
  },
  components: {
    'parent-com': parent
  }
}

</script>