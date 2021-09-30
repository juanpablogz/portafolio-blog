<template>
<div>
  <footer class="footer" style="margin-top: 65px" v-if="$colorMode.preference == 'light'" >
   <a href="https://www.facebook.com/juanpablo.gomezzapata.58" target="_blank"><img  class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625951104/fb_ywgmpl.png" alt=""></a>
   <a href="https://www.linkedin.com/in/juan-pablo-gomez-zapata-b9a50a17b/" target="_blank"> <img class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625951197/Linkedin_koq1vt.png" alt=""></a>
   <a href="" target="_blank"><img class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625951212/Group_1_rra0ol.png" alt=""></a>
  </footer>
  <footer class="footer" style="margin-top: 65px" v-if="$colorMode.preference == 'dark'" >
  <a href="https://www.facebook.com/juanpablo.gomezzapata.58" target="_blank"> <img  class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625953180/fb_1_peeeps.png" alt=""></a>
   <a href="https://www.linkedin.com/in/juan-pablo-gomez-zapata-b9a50a17b/" target="_blank"><img class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625953217/Linkedin_1_iajeyz.png" alt=""></a>
   <a href="" target="_blank"><img class="img-footer" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625953232/Group_3_raxotx.png" alt=""></a>
  </footer>
    <div class="footer">Copyright ©2021 All rights reserved </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
.footer {
  display: flex;
  justify-content: center;
  margin-top: 15px;
}
.img-footer {
  padding-right: 15px;
}
</style>