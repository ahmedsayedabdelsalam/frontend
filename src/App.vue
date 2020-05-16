<template>
    <div class="bg-gray-400" id="app">
        <div class="pt-16 mx-auto h-screen w-5/6">
            <div class="grid grid-cols-3 gap-4">
                <div class="bg-white rounded-lg p-3 clearfix shadow-lg h-24">
                    <img src="./assets/images/sketch.png" alt="sketch logo" class="float-left"/>
                    <div class="float-left ml-5">
                        <div class="text-indigo-700 text-2xl">Chat UI Kit <span class="text-sm">v.1</span></div>
                        <div class="text-orange-500 font-medium text-2xl">FREE DOWNLOAD</div>
                    </div>
                </div>
                <div class="bg-white rounded-lg p-5 shadow-lg">
                    <p class="ml-5 mb-2 text-gray-600">Find an answer from helpcenter</p>
                    <div class="bg-indigo-100 rounded-full p-3 clearfix">
                        <input type="text" class="text-gray-600 bg-transparent ml-2 w-5/6 outline-none float-left"
                               placeholder="Your text…">
                        <img src="./assets/images/send.png" alt="send button" class="float-right mr-2">
                    </div>
                </div>
                <div class="bg-purple-600 rounded-lg p-5 clearfix shadow-lg h-24">
                    <div class="float-left w-16 bg-no-repeat h-16"
                         :style="{ backgroundImage: `url('${require('./assets/images/user.png')}')`,backgroundPosition: '50% 60%' }"></div>
                    <!--                    <img src="./assets/images/user.png" alt="sketch logo" class="float-left"/>-->
                    <div class="float-left ml-3">
                        <p class="text-gray-200">David</p>
                        <span class="text-gray-400 inline-block mt-2">14:20 pm</span>
                    </div>
                    <div class="float-right">
                        <div class="rounded-full bg-gray-300 w-2 h-2 m-2"></div>
                        <div class="rounded-full bg-gray-300 w-2 h-2 m-2"></div>
                        <div class="rounded-full bg-gray-300 w-2 h-2 m-2"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {};
</script>

<style src="./assets/styles/index.scss" lang="scss"></style>
