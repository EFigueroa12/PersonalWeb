<template> 
    <div class="law">
    <PathReveal></PathReveal>  
    <h1 class="title"> The Case Against Myself </h1>
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
.law .title{
    position:relative;
    left: -38%;
    top: 11%;
    color: black;
    font-family: Cormorant Garamond;
}
.law {
    width: 2100px;
    height:2000px;
    background-image: url('@/assets/lawyer.jpg');
    background-size: 1250px;
} 
</style>
