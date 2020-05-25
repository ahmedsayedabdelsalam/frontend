<template>
    <div class="bg-gray-400">
        <div class="pt-8 mx-auto h-screen w-5/6" style="min-width: 1200px">
            <div class="grid grid-cols-3 gap-4">
                <div>
                    <div class="bg-white rounded-lg p-3 flex shadow-lg h-24">
                        <img src="../assets/images/sketch.png" alt="sketch logo" class="w-1/5"/>
                        <div class="w-4/5 ml-5">
                            <div class="text-indigo-700 text-2xl">Chat UI Kit <span class="text-sm">v.1</span></div>
                            <div class="text-orange-500 font-medium text-2xl">FREE DOWNLOAD</div>
                        </div>
                    </div>

                    <div class="my-8">
                        <div class="bg-white rounded-lg p-5 shadow-lg">
                            <div class="flex items-center">
                                <div class="w-1/5 bg-no-repeat h-16"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-sm-3.png')}')`,backgroundPosition: '50% 60%' }"></div>
                                <div class="text-xl w-3/6 ml-3">
                                    <p class="text-gray-700">David</p>
                                </div>
                                <div class="w-2/6 text-center">
                                    <span class="text-gray-600">14:20 pm</span>
                                </div>
                            </div>
                            <div class="my-5">
                                <p class="text-gray-600 p-3 text-xl">
                                    Want to give us your email address? That way we can follow up in case we get
                                    disconnected.
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
                                    <img src="../assets/images/attachment.png" alt="attachment button">
                                </div>
                                <div class="w-1/3">
                                    <img src="../assets/images/smile.png" alt="smile button">
                                </div>
                                <div class="w-1/3">
                                    <img src="../assets/images/send.png" alt="send button">
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg shadow-lg py-10 px-8 my-8">
                        <p class="text-xl text-center text-purple-700">This chat session has ended</p>
                        <p class="text-md text-center text-gray-600 py-8">Thank you for chatting with us, if you can take a minutes and rate this chat:</p>
                        <div class="flex justify-around px-16">
                            <div>
                                <div class="rounded-xl w-20 h-20 bg-center bg-no-repeat flex" :style="{ backgroundImage: `url('${require('../assets/images/green-rect.png')}')`}">
                                    <img src="../assets/images/yes.png" class="m-auto content-center" alt="yes">
                                </div>
                                <p class="text-center text-gray-600 pt-2">Good</p>
                            </div>
                            <div>
                                <div class="rounded-xl w-20 h-20 bg-center bg-no-repeat flex" :style="{ backgroundImage: `url('${require('../assets/images/red-rect.png')}')`}">
                                    <img src="../assets/images/no.png" class="m-auto content-center" alt="no">
                                </div>
                                <p class="text-center text-gray-600 pt-2">Bad</p>
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
                                <img src="../assets/images/send.png" alt="send button" class="mx-auto">
                            </div>
                        </div>
                    </div>

                    <div class="my-8">
                        <div class="rounded-lg p-8 h-56 shadow-lg bg-cover bg-no-repeat"
                             :style="{backgroundImage: `url('${require('../assets/images/background-1.png')}`, backgroundPosition: 'center'}">
                            <div class="grid grid-cols-4 gap-2 mt-2">
                                <div class="bg-no-repeat h-20 bg-contain bg-center"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-3.png')}')`}"></div>
                                <div class="bg-no-repeat h-20 bg-contain bg-center"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-1.png')}')`}"></div>
                                <div class="bg-no-repeat h-20 bg-contain bg-center"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-2.png')}')`}"></div>
                                <div class="h-20 p-1">
                                    <div class="bg-no-repeat border rounded-2xl h-full border-gray-500 opacity-75 text-gray-500 leading-loose text-center text-xl leading-extra-loose">
                                        +6
                                    </div>
                                </div>
                            </div>
                            <button class="mt-6 bg-white py-3 px-6 text-purple-600 rounded-xl">Send a message</button>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-lg p-5 my-8">
                        <div class="bg-indigo-100 p-3 rounded-xl text-gray-600 ">
                            <div class="flex items-center">
                                <div class="w-1/4 mr-2">
                                    <div class="bg-no-repeat h-16"
                                         :style="{ backgroundImage: `url('${require('../assets/images/user-sm-1.png')}')`,backgroundPosition: '50% 56%' }"></div>
                                </div>
                                <div class="w-1/2 text-gray-600">
                                    OK its work!
                                </div>
                                <span class="text-gray-600 opacity-75 w-1/4 inline-block">14:20 pm</span>
                            </div>
                        </div>
                        <div class="bg-indigo-100 p-3 rounded-xl text-gray-600 my-2">
                            <div class="flex items-center">
                                <div class="w-1/4 mr-2">
                                    <div class="bg-no-repeat h-16"
                                         :style="{ backgroundImage: `url('${require('../assets/images/user-sm-3.png')}')`,backgroundPosition: '50% 56%' }"></div>
                                </div>
                                <div class="w-1/2 text-gray-600">
                                    Thank you.
                                </div>
                                <span class="text-gray-600 opacity-75 w-1/4 inline-block">18:25 pm</span>
                            </div>
                        </div>
                        <button class="mt-4 bg-purple-600 py-3 px-6 text-white rounded-xl">Send a message</button>
                    </div>
                </div>
                <div>
                    <div class="bg-purple-600 rounded-lg p-5 flex shadow-lg h-24">
                        <div class="w-1/5 bg-no-repeat h-16"
                             :style="{ backgroundImage: `url('${require('../assets/images/user.png')}')`,backgroundPosition: '50% 60%' }"></div>
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
                    <div class="bg-white rounded-lg shadow-lg p-5 my-8">
                        <div class="flex items-end my-4">
                            <div class="w-1/5 mr-2">
                                <div class="bg-no-repeat bg-bottom h-16"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-sm-3.png')}')`,}"></div>
                            </div>
                            <div class="w-4/5">
                                <div class="text-xs px-2 text-gray-600">John Due</div>
                                <div class="bg-indigo-100 py-4 px-8 rounded-xl text-gray-600">Hello, welcome to
                                    Bubble.<br>
                                    How may I assist you today?
                                </div>
                            </div>
                        </div>
                        <div class="flex justify-end items-end my-4">
                            <div class="w-1/5"></div>
                            <div class="bg-purple-600 py-4 px-8 rounded-xl inline-block text-white">
                                Hi, I need the new plan.
                            </div>
                        </div>
                        <div class="flex items-end my-4">
                            <div class="w-1/5 mr-2">
                                <div class="bg-no-repeat bg-bottom h-16"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-sm-3.png')}')`}"></div>
                            </div>
                            <div class="w-4/5">
                                <div class="text-xs px-2 text-gray-600">John Due</div>
                                <div class="bg-indigo-100 py-4 px-8 rounded-xl text-gray-600 ">Want to give us your
                                    email<br>
                                    address? That way we can<br>
                                    follow up in case we get<br>
                                    disconnected.
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-lg p-4 my-8">
                        <div class="flex items-end">
                            <div class="w-1/5 mr-2">
                                <div class="bg-no-repeat bg-bottom h-16"
                                     :style="{ backgroundImage: `url('${require('../assets/images/user-sm-1.png')}')`}"></div>
                            </div>
                            <div class="w-4/5">
                                <div class="bg-indigo-100 p-2 rounded-xl text-gray-600 inline-block">
                                    <span class="w-2 h-2 mx-1 bg-gray-500 rounded-full inline-block"></span>
                                    <span class="w-2 h-2 mx-1 bg-gray-500 rounded-full inline-block"></span>
                                    <span class="w-2 h-2 mx-1 mb-1 b-1 bg-gray-600 rounded-full inline-block"></span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Theme1"
    }
</script>

<style scoped>

</style>