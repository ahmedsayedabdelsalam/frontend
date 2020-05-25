<template>
    <div class="bg-dark-blue-900 h-screen">
        <div class="nav box-border grid grid-cols-12 items-center py-5  space-x-8">
            <div class="logo col-span-1 ml-5">
                <img src="../assets/images/h-logo.png" alt="">
            </div>
            <div class="search col-span-7 relative flex items-center" >
                <img src="../assets/images/search.png" alt="search" class="h-4 mx-3 absolute">
                <input type="text" placeholder="Search..." class="rounded-xl bg-dark-blue-800 shadow-gray-lg focus:outline-none focus:shadow-outline text-gray-500 w-full py-2 px-4 pl-10">
            </div>
            <div class="actions col-span-4 flex items-center">
                <div class="buttons space-x-10 mx-12">
                    <button class="p-1 rounded-lg shadow-gray-md focus:outline-none focus:shadow-outline">
                        <img src="../assets/images/settings.png" alt="settings">
                    </button>
                    <button class="p-1 rounded-lg shadow-gray-md focus:outline-none focus:shadow-outline">
                        <img src="../assets/images/bell.png" alt="bell">
                    </button>
                </div>
                <div class="profile flex items-center space-x-3 mr-5">
                    <img src="../assets/images/avatar-1.png" alt="avatar">
                    <p class="text-white">Jasica Wingelton</p>
                    <button class="focus:outline-none focus:shadow-outline">
                        <img src="../assets/images/shiv-down.png" alt="shiv-down">
                    </button>
                </div>
            </div>
        </div>


        <div class="grid grid-cols-12 items-center box-border  space-x-8">
            <div class="col-span-1">

            </div>
            <div class="col-span-7 h-64 bg-cover shadow-gray-lg rounded-xl px-8 py-5 font-mono" :style="{backgroundImage: `url('${require('../assets/images/bg-1.png')}')`}">
                <p class="text-4xl text-white font-serif">Hi Jasica!</p>
                <p class="text-blue-300 font-sans text-sm my-4">
                    Welcome Home! The air quality is good & Fresh you<br>
                    can go out today
                </p>
                <div class="weather text-white mt-8">
                    <div class="flex items-center">
                        <span class="text-lg">+25 &deg;C</span>
                        <img src="../assets/images/clouds.png" class="ml-3" alt="clouds">
                    </div>

                    <p class="text-sm">Outdoor temperature</p>
                    <p class="text-xs font-hairline">Fuzzy cloudy weather</p>
                </div>
            </div>
            <div class="col-span-4">

            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Theme2"
    }
</script>

<style scoped>

</style>