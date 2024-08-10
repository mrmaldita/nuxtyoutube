<template>
    <nav class="mt-1 w-full fixed top-0 z-10 bg-white shadow">
      <div class="mx-auto sm:px-6 lg:px-1">
        <div class="w-full flex items-center justify-between">
          
          <div class="flex items-center space-x-4">
            <button class="text-lg text-black p-2">
              <i class="fa fa-bars"></i>
            </button>
            <div class="flex items-center">
              <img src="~/assets/images/youtubelogo.png" class="w-[100px]" alt="YouTube Logo"/>
              <sup class="text-[10px] text-black">PH</sup>
            </div>
          </div>
  
          
          <div class="flex items-center space-x-2">
            <div class="flex items-center bg-white border rounded-full overflow-hidden">
              <input class="border-none rounded-l-full px-3 h-10 focus:outline-none" placeholder="Search"/>
              <button class="bg-gray-200 border-l border-gray-300 px-3 h-10 rounded-r-full">
                <i class="fa fa-search text-lg"></i>
              </button>
            </div>
            <button class="bg-gray-200 rounded-full p-2">
              <i class="fa fa-microphone text-2xl text-gray-600"></i>
            </button>
          </div>
  
          
          <div class="flex items-center space-x-6">
            <img src="~/assets/images/create-video.png" class="h-7" alt="Create Video"/>
            <div class="relative">
              <i class="far fa-bell text-2xl"></i>
              <span class="absolute top-3 right-0 transform translate-x-1/2 -translate-y-1/2 bg-red-700 text-white rounded-full text-[11px] px-1">6</span>
            </div>
            <img src="~/assets/images/pp.jpg" class="rounded-full w-8 h-8" alt="Profile Picture"/>
          </div>
        </div>
      </div>
    </nav>
  </template>
  