<template> 
    <div class="doc"> 
     <PathReveal></PathReveal>
     <div class="pour">
         <button @click="incrementCount" class="butt"> Pour </button>
         <div class="flasks">
         <div class="flask1" v-if="count == 1">
               <img src="@/assets/emptyFlask.jpg" width="180" height="210" >
         </div>
         <div class="flask2" v-if="count == 2">
               <img src="@/assets/first.jpg" width="250" height="240" >
         </div>
         <div class="flask3" v-if="count == 3">
               <img src="@/assets/half.jpg" width="250" height="245" >
         </div>
         <div class="flask4" v-if="count == 4">
               <img src="@/assets/fullFlask.jpg" width="250" height="250" >
         </div>
         </div>
     </div>
     <div class="last" v-if="count >= 4">
         <div class="glowPic">
            <img src="@/assets/glow.jpg" width="200" height="350" >
         </div>
         <div class="labPic">
            <img src="@/assets/lab.jpg" width="200" height="250" >
         </div>
     </div>
     <div class="cert" v-if="count >= 3">
         <div class="certPic">
            <img src="@/assets/certif.jpg" width="200" height="240" >
         </div>
            <div class="tubePic">
            <img src="@/assets/tub.jpg" width="200" height="350" >
         </div>
     </div>
     <div class="nueroCamp" v-if="count >= 2">
         <div class="neuroPic">
            <img src="@/assets/nuerocamp.jpg" width="200" height="240" >
         </div>
            <div class="friendPic">
            <img src="@/assets/pig.jpg" width="200" height="240" >
         </div>
            <div class="stitchPic">
            <img src="@/assets/stitch.jpg" width="200" height="240" >
         </div>
     </div>
    </div>  
    
</template>

<script>
import Nav from '@/components/nav.vue'
import PathReveal from '@/components/PathReveal.vue'
export default{
    name: "DrLiz",
    components:{
        PathReveal
    },
    data(){
      return{
         count:0
      }
    },
    methods:{
      incrementCount(){
         this.count += 1
         console.log(this.count)
         if(this.count == 5){
            this.count = 0
         }
      }
    }
}
</script>
<style>
.doc {
    width: 2000px;
    height:4000px;
    background-image: url('@/assets/doc.jpg');
}
.last{
   position:relative;
}
.last .glowPic{
   position:absolute; 
   left:270px; 
   top:-360px;
   z-index: 1;
}
.last .labPic{
   position:absolute; 
   left:700px; 
   top:50px;
   z-index: 1;
}
.nueroCamp .neuroPic{
   position:relative; 
   left:300px; 
   top:30px;
  
}
.nueroCamp .friendPic{
   position:relative; 
   left:20px; 
   top:-200px;

}
.nueroCamp .stitchPic{
   position:relative; 
   left:900px; 
   top:-800px;

}
.cert{
   position:relative;
}
.cert .certPic{
   position:absolute; 
   left:0px; 
   top:-200px;
   z-index: 1;
}
.cert .tubePic{
   position:absolute; 
   left:1000px; 
   top:-50px;
   z-index:1;
}
.pour{
   position:relative; 
    left:550px; 
    top:180px;
}
.pour .butt{
   position:relative; 
    left:60px; 
    z-index: 100%
}
.pour .flask2{
   position:relative;
   left: -0.8%;
}
.pour .flask3{
   position:relative;
   left: -1%;
}
.pour .flask4{
   position:relative;
   left: -1%;
}
.pour .flask1{
    position:relative;
    left: 0.5%;
    top: -100%;
}
</style>
