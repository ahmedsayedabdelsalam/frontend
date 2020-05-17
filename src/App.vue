<template>
    <div class="bg-gray-400" id="app">
        <div class="pt-16 mx-auto h-screen w-5/6">
            <div class="grid grid-cols-3 gap-4">
                <div>
                    <div class="bg-white rounded-lg p-3 flex shadow-lg h-24">
                        <img src="./assets/images/sketch.png" alt="sketch logo" class="w-1/5"/>
                        <div class="w-4/5 ml-5">
                            <div class="text-indigo-700 text-2xl">Chat UI Kit <span class="text-sm">v.1</span></div>
                            <div class="text-orange-500 font-medium text-2xl">FREE DOWNLOAD</div>
                        </div>
                    </div>

                    <div class="my-8">
                        <div class="bg-white rounded-lg p-5 shadow-lg">
                            <div class="flex items-center">
                                <div class="w-1/5 bg-no-repeat h-16"
                                     :style="{ backgroundImage: `url('${require('./assets/images/user.png')}')`,backgroundPosition: '50% 60%' }"></div>
                                <div class="text-xl w-3/6 ml-3">
                                    <p class="text-gray-700">David</p>
                                </div>
                                <div class="w-2/6 text-center">
                                    <span class="text-gray-600">14:20 pm</span>
                                </div>
                            </div>
                            <div class="my-5">
                                <p class="text-gray-600 p-3 text-xl">
                                    Want to give us your email address? That way we can follow up in case we get disconnected.
                                </p>
                            </div>
                        </div>

                        <div class="bg-white rounded-lg p-5 flex items-center shadow-lg mt-3">
                            <div class="w-2/3">
                                <input type="text" class="text-gray-600 ml-2 w-5/6 outline-none"
                                       placeholder="Type your message…">
                            </div>
                            <div class="w-1/3 flex">
                                <div class="w-1/3">
                                    <img src="./assets/images/attachment.png" alt="attachment button">
                                </div>
                                <div class="w-1/3">
                                    <img src="./assets/images/smile.png" alt="smile button">
                                </div>
                                <div class="w-1/3">
                                    <img src="./assets/images/send.png" alt="send button">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="h-32 bg-white rounded-lg p-5 shadow-lg">
                        <p class="ml-5 mb-2 text-gray-600">Find an answer from helpcenter</p>
                        <div class="bg-indigo-100 rounded-full items-center p-3 flex content-between">
                            <input type="text" class="text-gray-600 bg-transparent ml-2 w-5/6 outline-none"
                                   placeholder="Your text…">
                            <div class="w-1/6">
                                <img src="./assets/images/send.png" alt="send button" class="mx-auto">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-purple-600 rounded-lg p-5 flex shadow-lg h-24">
                    <div class="w-1/5 bg-no-repeat h-16"
                         :style="{ backgroundImage: `url('${require('./assets/images/user.png')}')`,backgroundPosition: '50% 60%' }"></div>
                    <div class="w-3/5 ml-3">
                        <p class="text-gray-200">David</p>
                        <span class="text-gray-400 inline-block mt-2">14:20 pm</span>
                    </div>
                    <div class="w-1/5">
                        <div class="rounded-full bg-gray-300 w-2 h-2 my-2 mx-auto"></div>
                        <div class="rounded-full bg-gray-300 w-2 h-2 my-2 mx-auto"></div>
                        <div class="rounded-full bg-gray-300 w-2 h-2 my-2 mx-auto"></div>
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
