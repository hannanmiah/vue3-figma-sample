<script setup></script>

<template>
    <div class="bg-[#F0AD24] w-[1267px] h-[116px] px-2 md:px-4 shadow-lg rounded-md flex space-x-2 md:space-x-4 mx-auto justify-between items-center">
        <div class="w-[74px] h-[74px] rounded-full bg-white text-[#00FF19] font-bold grid place-items-center"><span class="text-sm text-center flex items-center flex-wrap">35 XP</span></div>
        <div class="flex flex-col items-center">
            <h5 class="text-white font-bold">Teacher: Name of teacher</h5>
            <span class="inline-block bg-[#FF5866] text-white px-2 py-1 rounded-md">DD.MM.YY</span>
        </div>
        <div class="bg-white h-[78px] w-1"></div>
        <div class="flex flex-col space-y-1 md:space-y-2">
            <span class="inline-block py-1 bg-[#561BFB] rounded-full text-white text-center text-sm">Type of Tasks</span>
            <h4 class="font-bold text-white">Name of Course</h4>
        </div>
        <div>
            <p class="text-white">To display long enough text in the description</p>
        </div>
        <div class="w-[74px] h-[74px] rounded-full bg-white text-black grid place-content-center"><span class="text-sm text-center flex items-center flex-wrap">0/3 attempt</span></div>
        <div class="flex space-x-2 md:space-x-3">
            <button class="btn btn-secondary">Preview</button>
            <button class="btn btn-primary">Expire</button>
        </div>
    </div>
</template>