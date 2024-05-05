<script>
  import WelcomeItem from '@/components/WelcomeItem.vue'
  import ActSixCap from '@/components/ActSixCap.vue'
  import NotFound from '@/components/NotFound.vue'
  import Nav from '@/components/nav.vue'
  import DrLiz from '@/components/DrLiz.vue'
  import LawyerLiz from '@/components/LawyerLiz.vue'
  import DrDepalma from '@/components/DrDepalma.vue'
  import identity from '@/components/identity.vue'
  import EndFinish from '@/components/EndFinish.vue'

  export default {
    name:'App',
    components:{
      WelcomeItem,
      ActSixCap,
      NotFound,
      Nav,
      DrLiz,
      LawyerLiz,
      DrDepalma,
      identity,
      EndFinish
    },
    computed: {
      currentComponent() {
      console.log(window.location.pathname.substring(1))
      return window.location.pathname.substring(1) != '' ? window.location.pathname.substring(1) : 'ActSixCap'
      }
    }
  }

</script>

<template>
  <component :is="currentComponent"></component>
</template>

