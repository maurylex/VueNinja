<template>
    <div class="card" style="width: 18rem;">
        <div class="card-header">
<img src="../assets/logo.png" class="card-img-left myimg-card" alt="">
 <h5 class="card-title">{{msg}}</h5>
        </div>
  
  <div class="card-body">
   
    <p class="card-text"><span>{{category}}</span></p>
    <p class="card-text">{{description}}</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
</template>

<script>
export default {

    props: [
        'msg', 'category','description' 
    ],

   
   
    name: "NavbarComponent"
}
</script>

<style >
.myimg-card{

size: 20px;

}
</style>