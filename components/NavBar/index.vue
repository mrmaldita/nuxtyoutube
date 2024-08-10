<template>
    <nav class="mt-1 w-full fixed top-0 z-10 overflow-hidden">
        <div class="mx-auto  sm:px-6 lg:px-1">
            <div class="  w-full flex z-10">
                <div class="pt-2 px-2">
                    <i class="fa fa-bars text-lg px-2 mt-1.5 text-black"></i>
                </div>
                <div class="flex items-center">
                    <img src="~/assets/images/youtubelogo.png" class="w-[100px] mr-0.5 mt-2"/>
                    <sup class="text-[10px] text-black">PH</sup>
                </div>
                <div class="w-fit mx-auto flex" >
                    <span class="rounded-full mx-auto w-fit flex items-center my-1">
                    <input class="border rounded-tl-full rounded-bl-full px-3 h-10" placeholder="Search"  />
                        <span class="bg-gray-200 border-l border-gray-300 rounded-tr-full rounded-br-full px-3 h-10">
                            <i class="fa fa-search text-lg pt-1.5 flex " aria-hidden="true"></i>
                        </span>       
                    </span>
                    <span class="bg-gray-200 rounded-full h-9 w-8 ml-2 px-2 mt-1">
                        <i class="fa fa-microphone text-2xl pt-1 flex" aria-hidden="true"></i>
                    </span>
                </div>
                <div class="flex">
                        <div class="flex">
                        <img src="~/assets/images/create-video.png" class="px-20 h-8 mt-1.5" />
                        <span>
                            <i class="far fa-bell text-2xl mt-1.5"></i>
                            <sup class="text-white bg-red-700 rounded-full text-[7px] px-0.5 -ml-1" >6</sup>
                        </span>
                        </div>
                        <div class="flex">
                       
                        </div>
                        <img src="~/assets/images/pp.jpg" class="rounded-full w-3.5 h-3.5 mx-2 mt-1" />
                </div>
            </div>
        </div>
    </nav>
</template>