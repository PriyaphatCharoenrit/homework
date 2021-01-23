<template>
    <div>
        <div class="Student"> 
            <h1>{{Student.title}}</h1><br/>

            <div style="width:100%;text-align:middle;">
                <img style="float: middle;padding:20px" width="200px" v-bind:src="Student.picture" /><br/>
                <div style="pidding:20px">
                    <b>StudentId:</b>{{Student.StudentId}}<br/>
                    <br/><b>FirstName:</b>{{Student.FirstName}}<br/>
                    <br/><b>LastName:</b>{{Student.LastName}}<br/>
                    <br/><b>weight:</b>{{Student.weight}}<br/>
                    <br/><b>height:</b>{{Student.height}}<br/>
                </div>
            </div><br/>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Student',
  components: {

  },
  props:["Student"]
  
}
</script>

<style>
.Student{
    width: 70%;
    background: greenyellow;
    padding: 10px;
    border-bottom: 10px rgb(0, 0, 0) dotted;
}
</style>