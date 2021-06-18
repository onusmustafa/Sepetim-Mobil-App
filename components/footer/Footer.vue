<template>
  <div class="footer">
   <footer class="bg-light text-center text-lg-start">
  <!-- Copyright -->
  <div class="p">
    © 2020 Copyright / 
    <a class="text-dark" href="#">Süleyman Demirel Üniversitesi</a>
  </div>
  <!-- Copyright -->
</footer>
  </div>
</template>

<script>
export default {
  name: 'VmFooter',
}
</script>

<style lang="scss" scoped>
 .footer {
   background: #b9e2fc;
   color: black;
   display: flex;
   align-items: center;
   justify-content: center;
   margin-top: 50px;
      p{
        text-align: center;
      }
 }
</style>
