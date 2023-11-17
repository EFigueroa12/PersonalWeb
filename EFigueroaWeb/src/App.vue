<script>
  import WelcomeItem from '@/components/WelcomeItem.vue'
  import ActSixCap from '@/components/ActSixCap.vue'
  import NotFound from '@/components/NotFound.vue'
  import Nav from '@/components/nav.vue'

  export default {
    name:'App',
    components:{
      WelcomeItem,
      ActSixCap,
      NotFound,
      Nav
    },
    computed: {
      currentComponent() {
      console.log(window.location.pathname.substring(1))
      return window.location.pathname.substring(1) != '' ? window.location.pathname.substring(1) : 'AvailableSpaces'
      }
    }
  }

</script>

<template>
  <component :is="currentComponent"></component>
</template>

<style scoped>

</style>
