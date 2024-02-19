<template>
<div  class="bgimg flex  text-black justify-center" style="margin-left: 750px; margin-top: 70px;">
    <img src="/public/cafe1.jpg" class="bgimg">
    <div class="loginblock bg-orange-200  rounded-3xl font-bold">
        <div class="bg-red-500 h-10 w-10 ml-44 mt-5">   
            logo
        </div>
        <div class="bg-black w-cover h-1">
        </div>
        <br>
        <div class=" mt-5 ml-2 text-2xl">
            Email
        </div>
        <div class="flex w-52 mt-2 tems-center rounded-[28px] p-[8px] bg-white border border-solid border-black" >
            <span class="pr-2"> 
                  <i class="fa-solid "></i>
            </span>
            <input type="" placeholder="Enter" class="bg-transparent focus:outline-none placeholder:text-black">
        </div>
        <br>
        <div class=" mt-5 ml-2 text-2xl">
            password
        </div>
        <div class="flex w-52 mt-2 tems-center rounded-[28px] p-[8px] bg-white border border-solid border-black" >
            <span class="pr-2"> 
                  <i class="fa-solid "></i>
            </span>
            <input type="" placeholder="Enter" class="bg-transparent focus:outline-none placeholder:text-black">
        </div>
        <br>
        <br>
        <div class="flex flex-row justify-between mx-5 text-black hover:font-bold">
            <button>
                <a href="registerpage1" class=" hover:text-gray-600">
                    Register
                </a>
            </button>
            <button>
                <a href="forgotpage1" class="hover:text-gray-600">
                    Forgot Password
                </a>
            </button>
        </div>
        <br>
        <br>
        <div class="flex justify-center">
            <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded">
                Login
            </button>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 're1.vue'
}
</script>

<style>
.bgimg{
    position: fixed;
    top: 0;
    left: 0;
    z-index: -1;
}
.loginblock{
    height: 600px;
    width: 400px;
    margin-top: 100px;
    border: solid;
    border-color:forestgreen;
}
</style>