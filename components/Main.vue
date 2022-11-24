<template>
    <div class="main-container w-[754px] h-[840px] flex justify-center items-center max-[600px]:items-start">
     <div class="invisible max-[600px]:visible bg-[#404555] h-[42px] w-[42.66px] relative left-[105px] top-[40px] rounded-full">
      <img src="../assets/mobile-icons/logo/Path 660.svg" alt="white" class="top-[14.37px] left-[16.98px] inline-block absolute z-20">
      <img src="../assets/mobile-icons/logo/Path 659.svg" alt="yellow" class="yellow top-[11.03px] left-[7.74px] inline-block absolute z-10">
      <img src="../assets/mobile-icons/logo/Ellipse 2.svg" alt="v-white" class="top-[24.98px] absolute left-[29.16px] inline-block z-30">
    </div>        
      <form class="flex flex-col max-[600px]:relative max-[600px]:top-[122px]">
          
            <h1 class="text-2xl font-bold mb-1 max-[600px]:text-[21px] max-[600px]:leading-7">Sign In to WisdomCircle</h1>
            <p class="text-[#404555] mb-6 max-[600px]:text-[14px] max-[600px]:leading-[22px]">Don’t have an account? Sign Up</p>
            <input type="text" placeholder="Email or Mobile Number" class="border border-[#DCDEE5] py-3 px-4 mb-4 rounded">
           <label for="password" class="border border-[#DCDEE5] py-3 px-4"><input type="password" placeholder="Password" id="password" /><input type="checkbox" @click="myFunction()" /></label> 
            <a href="" class="font-semibold mt-1 mb-6 text-right text-[#2558E5] max-[600px]:text-[12px]">Forgot password</a>
            <button class="bg-[#F1C12B] py-[11px] text-[#121317] font-semibold px-[32px] text-[18px] rounded max-[600px]:py-2 max-[600px]:text-base max-[600px]:relative max-[600px]:top-[254px]">Sign In</button>
        </form>
    </div>
</template>

<script setup>
function myFunction() {
  var x = document.getElementById("password");
  if (x.type === "password") {
    x.type = "text";
  } else {
    x.type = "password";
  }
}
</script>

<style scoped>
@import url(https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap%27);
.main-container {
    font-family: 'Poppins', sans-serif;
}
a {
    font-size: 14px;
    line-height: 22px;
}

</style>