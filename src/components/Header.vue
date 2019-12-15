<template>
  <div>
      <b-nav>
    <b-nav-item disabled><b>Fancy Quiz App</b></b-nav-item>
    <b-nav-item disabled>{{numCorrect}}/{{numTotal}}</b-nav-item>
  </b-nav>
  </div>
</template>

<script>
export default {
  props:[
    "numTotal",
    "numCorrect"
  ]
}
</script>
 
