<template> 
    <div class="com">
    <PathReveal></PathReveal>
    <h1 class="title"> The Computation of Liz </h1>
    <div class="question">
        <h1 class="label"> cout >> Do You Like Math? </h1><br>
        <div class="in">
            <button class="butt" @click="popUpHello"> Yes </button>
            <button class="butt" @click="popUpBook"> No </button>
        </div>
        <div v-if="show" class="helloW"> 
            <img src="@/assets/depalm/helloWorld.jpg" width="250" height="240" >
        </div>
        <div v-if="book" class="shelf">
            <img src="@/assets/depalm/book.jpg" width="300" height="340" >
        </div>
    </div>
    <div class="response">
    </div>
    
    </div>
 </template>
 <script>
import Nav from '@/components/nav.vue'
import PathReveal from '@/components/PathReveal.vue'
export default{
    name: "DrDepalma",
    components:{
        PathReveal
    },
    data(){
        return{
            show:false,
            book: false
        } 
    },
    methods:{
        popUpHello(){
            this.show = !this.show
            this.book = false
        },
         popUpBook(){
            this.book = !this.book
            this.show = false
        }
    }
}
</script>
<style>
.title{
   position:relative; 
    left:-400px; 
    top:2px;
   color: black;
    font-family: Cormorant Garamond;
}
.com {
    width: 2000px;
    height:2000px;
    background-image: url('@/assets/natty.jpg');
    background-size: 1200px;
}
.question{
    width: 50%;
    margin: auto;
}
.question .label{
    position:relative; 
    left:-69px; 
    top:2px;
}
.label{
    color: #000; /* Black color */
    font-family: Cormorant Garamond;
}
.butt {
  display: inline-block;
  padding: 10px 20px;
  font-size: 20px;
  text-align: center;
  text-decoration: none;
  cursor: pointer;
  border: 2px solid #fff; /* Border color */
  color: #fff; /* Text color */
  background-color: #3498db; /* Background color */
  border-radius: 10px;
  transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
}

/* Hover effect */
.butt:hover {
  background-color: #2980b9; /* Darker background color on hover */
  border-color: #2980b9; /* Darker border color on hover */
  color: #fff; /* Text color on hover */
}
.helloW{
    position:relative; 
    left:-50px; 
    top:10px;
}
.shelf{
    position:relative; 
    left:-70px; 
    top:15px;
}
html, body {
    max-width: 100%;
    overflow-x: hidden;
}
</style>