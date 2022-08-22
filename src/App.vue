<template>

<div>
 <AppHeading v-for=" person in persons"
 :key="person.id"
 :id="person.id"
 :name="person.name"
 :age="person.age"
 :height="person.height"
 :nationality="person.nationality"
 :gender="person.gender"
 ></AppHeading>
</div>



 
</template>

<script>
import AppHeading from "./components/appHeading.vue";

export default {
  components: {
  
    AppHeading
},

data(){
  return{
    persons:[{
        id:"pes",
        name:"Markus Merk",
        age: "20",
        height:"1,73",
        nationality:"German",
        gender:"male"
        }
    
    ]
  }
}
};
</script>
