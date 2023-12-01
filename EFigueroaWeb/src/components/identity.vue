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
        <img class="img" src="@/assets/more/game.jpg" width="270" height="190">
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
        <img class="img" src="@/assets/depalm/anna.jpg" width="200" height="190">
    </div>
    <div class="col">
        <img class="img" src="@/assets/depalm/rome.jpg" width="190" height="200">
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
    <div class="kevin">
        <img class="img" src="@/assets/more/kevin.jpg" width="170" height="190">
    </div>
    <div>
        <a class="butt" href="/EndFinish"> Does it end here? </a></div>
  </div>
    
</template>
 <script>
import Nav from '@/components/nav.vue'
import PathReveal from '@/components/PathReveal.vue'
import EndFinish from '@/components/EndFinish.vue'
export default{
    name: "identity",
    components:{
        PathReveal,
        EndFinish
    }
}
</script>
<style>
.title{
   text-align: center;
   color: black;
}
.id .butt{
    animation: fadeInButton 70s;
    position:relative; 
    left:320px; 
    top:-3470px;
    z-index:1;
    display: inline-block;
    padding: 10px 20px;
    font-size: 60px;
    text-align: center;
    text-decoration: none;
    cursor: pointer;
    border: 2px solid #3498db; /* Border color */
    color: white; /* Text color */
    background-color: #3498db; /* Background color 3498db */
    border-radius: 5px;
    transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
}
/* Hover effect */
.id .butt:hover {
  background-color: #2980b9; /* Darker background color on hover */
  border-color: #2980b9; /* Darker border color on hover */
  color: #fff; /* Text color on hover */
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
    animation: fadeIn 5s;
}
.fade-in-image2{
  animation: fadeIn 5s;
  position:absolute; 
   left:10px; 
   top:50px;
   z-index: 1;
}
.eli{
    animation: fadeIn 7s;
    position:relative; 
    left:0px; 
    top:350px;
}
.tech{
    animation: fadeIn 10s;
    position:relative; 
    left:900px; 
    top:-100px;
}
.tech2{
    animation: fadeIn 10s;
    position:relative; 
    left:600px; 
    top:-130px;
}
.jen{
    animation: fadeIn 15s;
    position:relative; 
    left:240px; 
    top:-390px;
}
.game{
    animation: fadeIn 17s;
    position:relative; 
    left:150px; 
    top:-1020px;
}
.shrek{
    animation: fadeIn 17s;
    position:relative; 
    left:55px; 
    top:-950px;
}
.kevin{
    animation: fadeIn 17s;
    position:relative; 
    left:-20px; 
    top:-3300px;
}
.annacat{
    animation: fadeIn 21s;
    position:relative; 
    left:790px; 
    top:-1350px;
}
.catemma{
    animation: fadeIn 21s;
    position:relative; 
    left:270px; 
    top:-1300px;
    z-index:1;
}
.bday{
    animation: fadeIn 30s;
    position:relative; 
    left:430px; 
    top:-1500px;
}
.pump{
    animation: fadeIn 24s;
    position:relative; 
    left:1000px; 
    top:-1530px;
}
.pump2{
    animation: fadeIn 24s;
    position:relative; 
    left:400px; 
    top:-1720px;
}
.twilight{
    animation: fadeIn 26s;
    position:relative; 
    left:650px; 
    top:-2300px;
}
.anna{
    animation: fadeIn 40s;
    position:relative; 
    left:450px; 
    top:-2450px;
    z-index:1;
}
.san2{
    animation: fadeIn 45s;
    position:relative; 
    left:420px; 
    top:-3200px;
}
.hall{
    animation: fadeIn 48s;
    position:relative; 
    left:720px; 
    top:-2770px;
    z-index:1;
}
.spain{
    animation: fadeIn 52s;
    position:relative; 
    left:250px; 
    top:-3220px;
    z-index:1;
}
.col{
    animation: fadeIn 55s;
    position:relative; 
    left:840px; 
    top:-2310px;
    z-index:1;
}
@keyframes fadeIn {
    0% { opacity:0; }
    85% { opacity:0; }
    100% { opacity:1; }
}
@keyframes fadeInButton {
    0% { opacity:0; }
    95% { opacity:0; }
    100% { opacity:1; }
}

</style>