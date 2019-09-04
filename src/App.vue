<template>
  <div> 
    <parent-com></parent-com>
  </div>
</template>

<script>
import parent from './parent.vue'

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
