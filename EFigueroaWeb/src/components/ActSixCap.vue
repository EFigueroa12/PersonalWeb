<template>  
  <h1>ACT SIX</h1><br>
  <a class="btn" href="/DrLiz" @click="doSum"> Dr.Liz </a><br><br>
  <a id="law" class="twobtn" href="/LawyerLiz" @click="doSum"> Lawyer Liz </a><br><br>  
  <a id="depalm" class="threebtn" href="/DrDepalma" @click="doSum"> Dr. Depalma </a><br><br>
  <a id="iden" class="fourbtn" href="/identity" @click="doSum"> Identity  </a><br><br>
</template>

<script>
  import nav from '@/components/nav.vue'
  import DrLiz from '@/components/DrLiz.vue'
  import LawyerLiz from '@/components/LawyerLiz.vue'
  import DrDepalma from '@/components/DrDepalma.vue'
  import identity from '@/components/identity.vue'
  import PathReveal from '@/components/PathReveal.vue'
  import EndFinish from '@/components/EndFinish.vue'

  export default{
    name: "ActSixCap",
    components:{
      DrLiz,
      PathReveal
    }
  }
</script>


<style>
.twobtn, .threebtn, .fourbtn{
   opacity: 1;
}
.checker{
  display:none;
}


</style>
