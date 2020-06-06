<template>
  <div class="bg-dark-blue-800">
    <div class="nav box-border grid grid-cols-12 items-center py-5 space-x-8">
      <div class="logo col-span-1 ml-5">
        <img src="../assets/images/h-logo.png" alt />
      </div>
      <div class="search col-span-7 relative flex items-center">
        <img src="../assets/images/search.png" alt="search" class="h-4 mx-3 absolute" />
        <input
          type="text"
          placeholder="Search..."
          class="rounded-xl bg-dark-blue-700 shadow-gray-lg focus:outline-none focus:shadow-outline text-gray-500 w-full py-2 px-4 pl-10"
        />
      </div>
      <div class="actions col-span-4 flex items-center">
        <div class="buttons space-x-10 mx-12">
          <button class="btn">
            <img src="../assets/images/settings.png" alt="settings" />
          </button>
          <button class="btn">
            <img src="../assets/images/bell.png" alt="bell" />
          </button>
        </div>
        <div class="profile flex items-center space-x-3 mr-5">
          <img src="../assets/images/avatar-1.png" alt="avatar" />
          <p class="text-white">Jasica Wingelton</p>
          <button class="focus:outline-none focus:shadow-outline">
            <img src="../assets/images/shiv-down.png" alt="shiv-down" />
          </button>
        </div>
      </div>
    </div>

    <div class="grid grid-cols-12 items-start mt-4 box-border space-x-8">
      <div class="col-span-1"></div>
      <div
        class="col-span-7 h-64 bg-cover shadow-gray-lg rounded-xl px-8 py-5 font-mono"
        :style="{backgroundImage: `url('${require('../assets/images/bg-1.png')}')`}"
      >
        <p class="text-4xl text-white font-serif">Hi Jasica!</p>
        <p class="text-blue-300 font-sans text-sm my-4">
          Welcome Home! The air quality is good & Fresh you
          <br />can go out today
        </p>
        <div class="weather text-white mt-8">
          <div class="flex items-center">
            <span class="text-lg">+25 &deg;C</span>
            <img src="../assets/images/clouds.png" class="ml-3" alt="clouds" />
          </div>

          <p class="text-sm">Outdoor temperature</p>
          <p class="text-xs font-hairline">Fuzzy cloudy weather</p>
        </div>
      </div>
      <div class="col-span-4">
        <div class="bg-dark-blue-900 rounded-l-xl text-white p-4">
          <div class="flex justify-between">
            <h4 class="font-semibold text-lg">My Devices</h4>
            <div>
              <button class="btn px-3">
                ON
                <img
                  class="inline-block ml-4"
                  src="../assets/images/arrow-down-white.png"
                  alt="arrow down"
                />
              </button>
              <button class="btn ml-4 px-3">
                <img
                  class="inline-block"
                  src="../assets/images/arrow-right-white.png"
                  alt="arrow right"
                />
              </button>
            </div>
          </div>
          <div class="grid grid-cols-2 gap-3 mt-3">
            <div class="rounded-xl bg-purple-700 p-5">
              <div class="flex justify-between items-center">
                <div>
                  <img src="../assets/images/refridgerator.png" alt="refridgerator" />
                </div>
                <div class="flex items-center">
                  <span>ON</span>
                  <span class="bg-white rounded-full ml-2 w-10 h-5 inline-block">
                    <span
                      class="w-5 h-5 rounded-full inline-block float-right border border-white bg-purple-700"
                    ></span>
                  </span>
                </div>
              </div>
              <div class="font-semibold mt-4 leading-none">Refridgerator</div>
            </div>
            <div class="rounded-xl bg-blue-600 p-5">
              <div class="flex justify-between items-center">
                <div>
                  <img src="../assets/images/router.png" alt="refridgerator" />
                </div>
                <div class="flex items-center">
                  <span>ON</span>
                  <span class="bg-white rounded-full ml-2 w-10 h-5 inline-block">
                    <span
                      class="w-5 h-5 rounded-full inline-block float-right border border-white bg-blue-600"
                    ></span>
                  </span>
                </div>
              </div>
              <div class="font-semibold mt-4 leading-none">Router</div>
            </div>
            <div class="rounded-xl bg-orange-600 p-5">
              <div class="flex justify-between items-center">
                <div>
                  <img src="../assets/images/music-system.png" alt="refridgerator" />
                </div>
                <div class="flex items-center">
                  <span>ON</span>
                  <span class="bg-white rounded-full ml-2 w-10 h-5 inline-block">
                    <span
                      class="w-5 h-5 rounded-full inline-block float-right border border-white bg-orange-600"
                    ></span>
                  </span>
                </div>
              </div>
              <div class="font-semibold mt-4 leading-none">Music System</div>
            </div>
            <div class="rounded-xl bg-green-500 p-5">
              <div class="flex justify-between items-center">
                <div>
                  <img src="../assets/images/lamps.png" alt="refridgerator" />
                </div>
                <div class="flex items-center">
                  <span>ON</span>
                  <span class="bg-white rounded-full ml-2 w-10 h-5 inline-block">
                    <span
                      class="w-5 h-5 rounded-full inline-block float-right border border-white bg-green-500"
                    ></span>
                  </span>
                </div>
              </div>
              <div class="font-semibold mt-4 leading-none">Lamps</div>
            </div>
          </div>
          <div class="flex justify-between mt-5">
            <h4 class="font-semibold text-lg">Members</h4>
            <div>
              <button class="btn ml-4 px-3">
                <img
                  class="inline-block"
                  src="../assets/images/arrow-right-white.png"
                  alt="arrow right"
                />
              </button>
            </div>
          </div>
          <div class="rounded-xl shadow-gray-md flex justify-between mt-3 p-4">
            <div class="w-1/5 text-center">
              <img class="inline-block" src="../assets/images/jasica-avatar.png" alt="Jasica" />
              <div class="font-semibold text-md mt-2">Jasica</div>
              <div class="text-xs text-purple-300">Admin</div>
            </div>
            <div class="w-1/5 text-center">
              <img class="inline-block" src="../assets/images/nariya-avatar.png" alt="Nariya" />
              <div class="font-semibold text-md mt-2">Nariya</div>
              <div class="text-xs text-purple-300">Full Access</div>
            </div>
            <div class="w-1/5 text-center">
              <img class="inline-block" src="../assets/images/riya-avatar.png" alt="Riya" />
              <div class="font-semibold text-md mt-2">Riya</div>
              <div class="text-xs text-purple-300">Full Access</div>
            </div>
            <div class="w-1/5 text-center">
              <img class="inline-block" src="../assets/images/dad-avatar.png" alt="Dad" />
              <div class="font-semibold text-md mt-2">Dad</div>
              <div class="text-xs text-purple-300">Full Access</div>
            </div>
            <div class="w-1/5 text-center">
              <img class="inline-block" src="../assets/images/mom-avatar.png" alt="Mom" />
              <div class="font-semibold text-md mt-2">Mom</div>
              <div class="text-xs text-purple-300">Full Access</div>
            </div>
          </div>
          <div class="flex justify-between mt-5">
            <h4 class="font-semibold text-lg">Power Consumed</h4>
            <div>
              <button class="btn px-3">
                <img
                  class="inline-block mb-1"
                  src="../assets/images/calender-white.png"
                  alt="calender"
                />
                <span class="ml-2">Month</span>
                <img
                  class="inline-block ml-4"
                  src="../assets/images/arrow-down-white.png"
                  alt="arrow down"
                />
              </button>
              <button class="btn ml-4 px-3">
                <img
                  class="inline-block"
                  src="../assets/images/arrow-right-white.png"
                  alt="arrow right"
                />
              </button>
            </div>
          </div>
          <div class="rounded-xl shadow-gray-md mt-3 p-4">
            <div class="flex justify-between">
              <div>
                <span
                  class="w-5 h-5 rounded-full border border-red-600 inline-flex items-center justify-center"
                >
                  <span class="w-3 h-3 rounded-full bg-red-600 inline-block"></span>
                </span>
                <span class="text-md ml-2">Electricity Consumed</span>
              </div>
              <div class="text-red-600 text-md">73% Spending</div>
            </div>
            <div class="mt-3 flex">
              <img src="../assets/images/percentages.png" alt="percentages" />
              <div>
                <img src="../assets/images/graph.png" alt="graph" />
                <img src="../assets/images/months.png" alt="months" />
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
  name: "Theme2"
};
</script>

<style scoped>
</style>