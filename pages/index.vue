<template>
  <div>
    <div class="darker" style="z-index:-999;">&nbsp;</div>

    <Container class="min-h-screen">
      <div class=" mt-96 mb-28 grid grid-cols-1 xl:grid-cols-2 gap-2">
       <div>
         <h1 class="text-5xl xl:text-7xl text-center text-head text-white" style="" >เฮ้ ฉันคือ Feezial</h1>
         <p class="my-2 text-start text-center text-xl xl:text-left xl:mx-16 xl:text-3xl text-bottom" style=" font-family: 'Kanit', sans-serif;">&nbsp;Front-end Developer</p>
       </div>
       <div>
        <img src="https://media.discordapp.net/attachments/1047537581044289628/1049241471540285460/code.png" class="rounded-xl w-64 mx-auto xl:w-96 animate__animated animate__tada animate__infinite animate__slow " alt="">
        <!-- <a class="px-20 cursor-pointer rounded-2xl py-2 text-xl text-center text-white font-semibold mx-auto inline bg-button hover:-translate-y-10 duration-500 hover:shadow-lg" style="box-shadow:5px 4px 0px 0px rgba(255, 255, 255, 0.7) ; font-family: 'Kanit', sans-serif;"><img src="https://media.discordapp.net/attachments/963339136935297064/1048641097322221688/unknown.png"  class=" w-16 inline-block" > &nbsp;&nbsp; Contact Me</a> -->
       </div>
      </div>
      <div class=" mx-auto table">
        <a href="https://github.com/Feezial" target="_blank" class="text-center font-semibold xl:inline-block mx-10 hover:scale-90 transition-all duration-500 hover:shadow-lg ">
          <img src="https://media.discordapp.net/attachments/1047537581044289628/1049008815745531954/space-travel.png" class=" w-24 mx-auto animate__animated animate__bounce animate__infinite animate__slower animate__delay-2s" alt="">
          <h1 class="text-xl font-bold text-bottom " >Github</h1>
        </a>
        <a href="https://www.instagram.com/fee_878/" target="_blank" class="text-center font-semibold xl:inline-block mx-10">
          <img src="https://media.discordapp.net/attachments/1047537581044289628/1049008448366452837/camera.png" class=" w-20 mx-auto animate__animated animate__bounce animate__infinite animate__slower animate__delay-3s" alt="">
          <h1 class="text-xl font-bold text-bottom" >Instagram</h1>
        </a>
        <a href="" class="text-center font-semibold xl:inline-block mx-10">
          <img src="https://media.discordapp.net/attachments/1047537581044289628/1049008247782252664/twitter_2.png" class=" w-20 mx-auto animate__animated animate__bounce animate__infinite animate__slower animate__delay-4s" alt="">
          <h1 class="text-xl font-bold text-bottom" >Twitter</h1>
        </a>
      </div>
    </Container>

    <Container>
      <div class="min-h-screen rounded-xl" style="background:rgba(0,0,0,0.5); ">
      <h1 class="text-center text-head text-4xl pt-20">ผลงาน และ ประสบการณ์</h1>
      <p class="box">EXEPRICE AND WORK </p>
      <Container class="my-24 text-center">
        <div>
          <h1 class="text-bottom font-semibold text-xl">ผลงาน ภายใต้ ( <span class="text-red-400">MultiLab Studio</span> )</h1>
          </div>
        <div class="grid grid-cols-1 gap-2 mx-auto table ">
          <div class="mx-auto table xl:px-72">
            <br><br>
            <img src="https://media.discordapp.net/attachments/1047537581044289628/1049357669842038865/image.png?width=1311&height=672" class="rounded-xl  shadow-box" alt="">
            <a href="https://onishop.me/" target="_blank" class="text-bottom text-left hover:-translate-y-5 trasition duration-500 my-3 text-lg px-5 py-2 rounded-md mb-20 box-sh">เข้าชม onishop</a>
          </div>
          <div class="mx-auto table xl:px-72">
            <br><br>
            <img src="https://media.discordapp.net/attachments/1047537581044289628/1049362895550554142/image.png?width=1315&height=672" class="rounded-xl  shadow-box" alt="">
            <a href="https://treebux.net/" target="_blank" class="text-bottom text-left my-3 text-lg px-5 py-2 rounded-md mb-20 box-sh">เข้าชม treebux</a>
          </div>
          <br><br>
        </div>
      </Container>
    </div>
    </Container>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style>
.box{
  @apply text-center font-semibold text-lg;
  color:rgba(255, 255, 255, 1.0);
}
.text-head{
 font-family: 'Kanit', sans-serif;
  /* color: #354259; */
  font-weight: 900; 
  letter-spacing: -0.125rem;
  text-shadow: 0 0 80px rgb(192 219 255 / 48%), 0 0 32px rgb(65 120 255 / 24%);
    color: rgba(255, 255, 255, 1.0);
}

.text-bottom{
  font-family: 'Kanit', sans-serif;
  text-shadow: 0 0 80px rgb(192 219 255 / 48%), 0 0 32px rgb(65 120 255 / 24%);
    color: rgba(255, 255, 255, 1.0);
}

.bg-button{
  background: #4568DC;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #B06AB3, #4568DC);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #B06AB3, #4568DC); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
color: white;
/* border: 3px solid #354259; */
margin: 0 auto;
display: table;

}

.shadow-box{
  box-shadow: 0 0 80px rgb(192 219 255 / 48%), 0 0 32px rgb(65 120 255 / 24%);
}

.box-sh{
  background: linear-gradient(to right, rgb(55, 65, 81), rgb(17, 24, 39), rgb(0, 0, 0));
  box-shadow: 0 0 80px rgb(192 219 255 / 48%), 0 0 32px rgb(65 120 255 / 24%);
  color: whitesmoke;
}
</style>