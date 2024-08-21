<script setup></script>

<template>
  <div class="home_container p-2">
    <div class="home_header flex mt-3 pl-4 pr-4">
      <div class="logo"><img class="w-[40%]" src="/src/assets/pictures/logo.png" alt="" srcset="" /></div>
      <button class="signIn pl-2 pr-2 border-solid	border-black border-2 rounded-xl">sign In <span class="pl-1"><i class='bx bx-user-circle'></i></span></button>
    </div>
    <div class="home_main flex justify-center ">
      <div class="home_main_content flex justify-center items-center flex-col	">
        <div class="pict w-[40%]">
          <img  src="/src/assets/pictures/epiflix.png" alt="" srcset="">
        </div>
          <p class="font-bold	mt-5">Unlimited movies, TV shows, and more.</p>
          <p class="font-normal text-sm pt-2">Watch anywhere. Cancel anytime.</p>
          <button class="text-3xl pl-3 pr-3 mt-6 pt-2 pb-2 rounded-lg font-bold">
            Get started
          </button>
      </div>
    </div>
  </div>
</template>


<style>

.home_main{
  height: 80vh;
  align-items: center
}
.home_main .home_main_content button{
  background-color: #D62D30;
  color: #fff;
}
.home_header{
  justify-content: space-between
}
</style>