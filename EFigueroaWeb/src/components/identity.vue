<template>
  <div class="id">
    <h1 class="title">Identity</h1>
    <PathReveal></PathReveal>
    <div class="fade-in-image">
        <img class="img" src="@/assets/depalm/sorority.jpg" width="200" height="250">
    </div> 
  </div>
    
</template>
 <script>
import Nav from '@/components/nav.vue'
import PathReveal from '@/components/PathReveal.vue'
export default{
    name: "identity",
    components:{
        PathReveal
    }
}
</script>
<style>
.title{
   text-align: center;
   color: black;
}
.id {
    width: 2000px;
    height:2000px;
    background-image: url('@/assets/GONZAGA.jpg');
    background-size: 1200px;
}

.fade-container {
  display: flex;
}

.fade-in-image{
  animation: fadeIn 20s;
 
}
@keyframes fadeIn {
  0%{opacity: 0;}
  100%{opacity:1;}
}

</style>