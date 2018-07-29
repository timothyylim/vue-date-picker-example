<template>
  <div id="app">
    <hello></hello>

  </div>
</template>

<script>
import Hello from './components/Hello.vue'
import Datepicker from './components/Datepicker.vue'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>
