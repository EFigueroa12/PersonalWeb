<template>
  <div class ="HeaderFrontPage">
    <h1> Elizabeth Figueroa </h1><br>
    <h3> The Progression of Self-Identity and Experience </h3><br>
    <h3> efigueroa@zagmail.gonzaga.edu | <a href="https://gonzagau-my.sharepoint.com/:w:/r/personal/efigueroa_zagmail_gonzaga_edu/Documents/Documents/College4/Resume.docx?d=w5009c6d3a155407ab8eea354cc023510&csf=1&web=1&e=WMDnDH"  target="_blank"> Resume </a> </h3><br>
    <a class="sixbtn" href="/ActSixCap"> Act Six Capstone </a><br><br>
    <a class="btn" href="https://gonzagau-my.sharepoint.com/:w:/r/personal/efigueroa_zagmail_gonzaga_edu/Documents/Documents/collegeyr3/spring2023/philtech/Sex%20Work%20in%20Technology%20Presentation%20Outline.docx?d=w09b7c89bf7fd44d3aec84c083e73a6b5&csf=1&web=1&e=yw5QTe" target="_blank"> Honors Thesis </a>
  </div>
  <div class="highschoolPic">
    <img src="@/assets/babyLiz.jpg" width="200" height="350" alt="n">
  </div>
  
</template>

<script>
import ActSixCap from '@/components/ActSixCap.vue'
import nav from '@/components/nav.vue'

</script>

<style scoped>
.HeaderFrontPage{
  text-align: "top-center";
}
.highschoolPic{
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;
  gap: 20px;
}
.btn, .sixbtn{
  text-decoration: none;
  padding: 0.5rem;
  border: 1px solid #33AB5F; /* lighter green border */
  background-color: #228B22; /* green color  */
  color: white; /* white color */
  cursor: pointer; /* Add a pointer cursor on hover */
}



</style>
