<template>
  <div class="id">
    <h1 class="title">Identity</h1>
    <PathReveal></PathReveal>
    <div class="fade-in-image">
        <img class="img" src="@/assets/depalm/sorority.jpg" width="250" height="250">
    </div> 
    <div class="fade-in-image2">
        <img class="img" src="@/assets/depalm/big.jpg" width="200" height="250">
    </div>
    <div class="eli">
        <img class="img" src="@/assets/depalm/eli.jpg" width="250" height="250">
    </div>
    <div class="tech">
        <img class="img" src="@/assets/depalm/tech.jpg" width="300" height="250">
    </div>
    <div class="tech2">
        <img class="img" src="@/assets/more/ish.jpg" width="300" height="250">
    </div>
    <div class="jen">
        <img class="img" src="@/assets/depalm/jen.jpg" width="200" height="150">
    </div>
    <div class="game">
        <img class="img" src="@/assets/more/game.jpg" width="250" height="190">
    </div>
     <div class="shrek">
        <img class="img" src="@/assets/more/shrek.jpg" width="200" height="190">
    </div>
    <div class="annacat">
        <img class="img" src="@/assets/more/annacat.jpg" width="200" height="190">
    </div>
    <div class="catemma">
        <img class="img" src="@/assets/more/catemma.jpg" width="200" height="190">
    </div>
    <div class="bday">
        <img class="img" src="@/assets/more/bday.jpg" width="400" height="200">
    </div>
    <div class="pump">
        <img class="img" src="@/assets/more/pump.jpg" width="200" height="190">
    </div>
    <div class="pump2">
        <img class="img" src="@/assets/more/pump2.jpg" width="200" height="190">
    </div>
    <div class="twilight">
        <img class="img" src="@/assets/more/twilight.jpg" width="200" height="190">
    </div>
    <div class="anna">
        <img class="img" src="@/assets/depalm/anna.jpg" width="170" height="190">
    </div>
    <div class="col">
        <img class="img" src="@/assets/depalm/rome.jpg" width="200" height="190">
    </div>
    <div class="hall">
        <img class="img" src="@/assets/depalm/hall.jpg" width="200" height="190">
    </div>
    <div class="san2">
        <img class="img" src="@/assets/depalm/san2.jpg" width="300" height="190">
    </div>
    <div class="spain">
        <img class="img" src="@/assets/depalm/spain.jpg" width="170" height="190">
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
.fade-in-image{
    position:absolute; 
    left:1000px; 
    top:-10px;
    z-index:1;
    animation: fadeIn 7s;
}
.fade-in-image2{
  animation: fadeIn 5s;
  position:absolute; 
   left:10px; 
   top:50px;
   z-index: 1;
}
.eli{
    animation: fadeIn 8s;
    position:relative; 
    left:0px; 
    top:300px;
}
.tech{
    animation: fadeIn 12s;
    position:relative; 
    left:900px; 
    top:-100px;
}
.tech2{
    animation: fadeIn 13s;
    position:relative; 
    left:600px; 
    top:-130px;
}
.jen{
    animation: fadeIn 16s;
    position:relative; 
    left:240px; 
    top:-350px;
}
.game{
    animation: fadeIn 17s;
    position:relative; 
    left:170px; 
    top:-950px;
}
.shrek{
    animation: fadeIn 17s;
    position:relative; 
    left:70px; 
    top:-950px;
}
.annacat{
    animation: fadeIn 20s;
    position:relative; 
    left:790px; 
    top:-1350px;
}
.catemma{
    animation: fadeIn 20s;
    position:relative; 
    left:230px; 
    top:-1280px;
}
.bday{
    animation: fadeIn 25s;
    position:relative; 
    left:430px; 
    top:-1500px;
}
.pump{
    animation: fadeIn 22s;
    position:relative; 
    left:1000px; 
    top:-1530px;
}
.pump2{
    animation: fadeIn 22s;
    position:relative; 
    left:400px; 
    top:-1690px;
}
.twilight{
    animation: fadeIn 19s;
    position:relative; 
    left:600px; 
    top:-2300px;
}
.anna{
    animation: fadeIn 30s;
    position:relative; 
    left:400px; 
    top:-2450px;
    z-index:1;
}
.san2{
    animation: fadeIn 32s;
    position:relative; 
    left:380px; 
    top:-3200px;
}
.hall{
    animation: fadeIn 32s;
    position:relative; 
    left:720px; 
    top:-2750px;
    z-index:1;
}
.spain{
    animation: fadeIn 34s;
    position:relative; 
    left:-30px; 
    top:-3120px;
    z-index:1;
}
.col{
    animation: fadeIn 34s;
    position:relative; 
    left:840px; 
    top:-2300px;
    z-index:1;
}
@keyframes fadeIn {
    0% { opacity:0; }
    85% { opacity:0; }
    100% { opacity:1; }
}

</style>