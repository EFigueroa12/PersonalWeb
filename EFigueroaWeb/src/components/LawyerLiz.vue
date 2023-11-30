<template> 
    <div class="law">
    <h1 class="title"> The Case Against Myself </h1>
    <PathReveal></PathReveal>
     <div class="debatePic">
        <img src="@/assets/freshDebate.jpg" width="270" height="240" >
     </div>
    </div>
</template>

<script>
import Nav from '@/components/nav.vue'
import PathReveal from '@/components/PathReveal.vue'
export default{
    name: "LawyerLiz",
    components:{
        PathReveal
    }
}
</script>
<style>
.title{
   text-align: center;
}
.law {
    width: 2000px;
    height:2000px;
    background-image: url('@/assets/lawyer.jpg');
    background-size: 1300px;
}
</style>
