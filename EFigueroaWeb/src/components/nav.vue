<template>
    
</template>
  
<script>


export default {
    name: 'App',
    computed: {
        currentComponent() {
        console.log(window.location.pathname.substring(1))
        return window.location.pathname.substring(1) != '' ? window.location.pathname.substring(1) : 'AvailableSpaces'
        }
    }
}
</script>

<style>


</style>