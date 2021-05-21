<template>
<div>

</div>
</template>

<script>
import axios from "axios";

export default {
name: "home",
  created() {
  axios({
    url:'http://localhost:3000/home'
  }).then(res=>{
    console.log(res);
  })
  }
}
</script>

<style scoped>

</style>