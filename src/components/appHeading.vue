<template>
  <div>
    <header>Die Person {{name}} is {{age}} jahre alt und kommt von {{nationality}}. Die person ist {{gender}} und {{height}} gßoss</header>
  </div>
</template>

<script>
export default {
  name:"appHeading",


  props:{
    id:String,
    height:String,
    age:String,
    name:String,
    nationality:String,
    gender:String,
  }
}
</script>


<style>
header {
  background-color: rebeccapurple;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 50px;
  position: absolute;
  top: 0;
  left: 0%;
  border-bottom: 2px solid black;
}
</style>
