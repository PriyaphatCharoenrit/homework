<template>
  <div id="app">
    <Students v-bind:student1="Students" />
  </div>
</template>

<script>
import Students from './components/Students.vue'

export default {
  name: 'App',
  components: {
    Students,
  },
data(){
  return{
    Students:[
        {
           "StudentId": "614234013",
           "FirstName": "Priyaphat",
           "LastName": "Charoenrit",
            "weight": 66,
            "height": 162,
            "picture": "https://raw.githubusercontent.com/PriyaphatCharoenrit/Pari/main/pari.jpg"
        },
        {
            "StudentId": "614234006",
            "FirstName": "Sineenart",
            "LastName": "Songsen",
            "weight": 52,
            "height": 156,
            "picture": "https://raw.githubusercontent.com/PriyaphatCharoenrit/Pari/main/kik.jpg"
        },
        {
            "StudentId": "614234011",
            "FirstName": "Phatcharida",
            "LastName": "Foytong",
            "weight": 56,
            "height": 159,
            "picture": "https://raw.githubusercontent.com/PriyaphatCharoenrit/Pari/main/baby.jpg"
        },
        {
            "StudentId": "614234012",
            "FirstName": "Naspat",
            "LastName": "Staremitakon",
            "weight": 63,
            "height": 162,
            "picture": "https://raw.githubusercontent.com/PriyaphatCharoenrit/Pari/main/gun.jpg"
        },
        {
            "StudentId": "614234024",
            "FirstName": "Suhana",
            "LastName": "Busamart",
            "weight": 45,
            "height": 153,
            "picture": "https://raw.githubusercontent.com/PriyaphatCharoenrit/Pari/main/nang.jpg"
        },
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
