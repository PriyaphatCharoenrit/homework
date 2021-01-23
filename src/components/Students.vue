<template>
<div>
    <div v-bind:key="Student.Studentid" v-for="Student in Student1">
        <Student v-bind:Student="Student" /><br/>
    </div>

    </div>
</template>

<script>
import Student from './Student.vue'
export default {
  name: 'Students',
  components: {
      Student,
  },
  props:["Student1"]
  
}
</script>

<style>

</style>