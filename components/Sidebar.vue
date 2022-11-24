<template>
    <div class="bg-[#404555] text-white relative h-[840px] w-[526px] left-0 top-0">
   <img src="../assets/icons/POSE_02.svg" alt="small-guy" class="h-219 w-165 left-0 top-[621px]">
   <img src="../assets/icons/Path 662.svg" alt="v-yellow" class="top-[216px] left-[155px]">
   <img src="../assets/icons/Path 664.svg" alt="v-white" class="top-[242px] left-[230px]">
   <img src="../assets/icons/Path 663.svg" alt="circle" class="top-[325.3643798828125px] left-[328.55126953125px]">
   <div class="text-area left-[165px] top-[525px] flex-col gap-3">
    <h3 class="font-bold text-2xl m-0 p-0" >Welcome back!</h3>
    <p class="w-[337px] text-lg text-left">Sign In to find opportunities that match your interests. We have both part-time and full-time roles that can be done online and in-person.</p>
 
</div>
   <div class="loading left-[165px] top-[713px] gap-[2.82px]">
    <div class="bg-white w-[15.06px] h-[3px]"></div>
    <div class="dot"></div>
    <div class="dot"></div>
   </div>
   <p class="contact-text w-[337px] top-[780px] left-[165px] text-xs">Please contact us at +91-9380644532 if you need any assistance.</p>
    </div>
</template>


<script setup>

</script>

<style scoped>

img, .text-area, .loading, .contact-text {

position: absolute;
    }

.text-area, .loading {
    display: flex;
}


.dot {
    background-color: white;
    width: 2.82px;
    height: 3px;
    opacity: 50%;
}



</style>