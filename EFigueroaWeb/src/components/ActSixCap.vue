<template>  
  <h1>ACT SIX</h1><br>
  <a class="btn" href="/DrLiz" @click="doSum"> Dr.Liz </a><br><br>
  <a id="law" class="twobtn" href="/LawyerLiz" @click="doSum"> Lawyer Liz </a><br><br>  
  <a id="depalm" class="threebtn" href="/DrDepalma" @click="doSum"> Dr. Depalma </a><br><br>
  <a id="iden" class="fourbtn" href="/identity" @click="doSum"> Identity  </a><br><br>
  <!-- <PathReveal :count="count" @update-count="updateCount"></PathReveal> -->
</template>

<script>
  import nav from '@/components/nav.vue'
  import DrLiz from '@/components/DrLiz.vue'
  import LawyerLiz from '@/components/LawyerLiz.vue'
  import DrDepalma from '@/components/DrDepalma.vue'
  import identity from '@/components/identity.vue'
  import PathReveal from '@/components/PathReveal.vue'

  export default{
    name: "ActSixCap",
    components:{
      DrLiz,
      PathReveal
    },
    data(){
      return{
        input: null,
        count: 1
      }
    },
    methods:{
      doSum(){
        this.count += 1
        console.log("next")
        console.log(this.count)
        if(this.count == 2){
          console.log("law 2")
          document.getElementById("law").style.opacity = 1;
        }
      },
      updateCount(newCount) {
      this.count = newCount;
      }
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
