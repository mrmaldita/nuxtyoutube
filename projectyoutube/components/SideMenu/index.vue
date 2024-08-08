<template>
    <div class="w-[250px] h-screen mt-4 px-2 fixed pt-16 overflow-hidden"> 
        <div class="h-full overflow-y-auto">
        <ul class="border-b border-gray-300 pb-3 mb-1">
        <li class="px-2 py-1 flex bg-gray-300 rounded-lg capitalize gap-3 items-center">
            <span class="text-xs py-1">
                <i class="fa fa-home text-black text-sm"></i>
            </span>
            <span class="flex-grow text-base ml-1 mt-1.5 mb-1.5 font-medium">Home</span>
        </li>
        <li class="px-2 py-1 flex hover:bg-gray-400 rounded-lg capitalize gap-3 items-center">
            <span class="-ml-1">
                <img src="~assets/images/shorts.png" class="h-6 w-6 ">
            </span>
            <span class="text-base mb-1">Shorts</span>
        </li>
        <li class="px-2 py-1 flex hover:bg-gray-400 rounded-lg capitalize gap-3">
            <span class="text-xs py-1">
                <img src="~assets/images/subs.png" class="w-4 h-5  ">
            </span>
            <span class="text-base ml-1 mt-0.5">Subscriptions</span>
        </li>
        </ul>
        <div class="mt-1">
            <ul class="border-b border-gray-300 pb-2 items-center">
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1 block">
                    <span class="text-base font-medium">You</span>
                    <i class="fa-thin fa-greater-than text- font-semibold text-xl   -mt-1"></i>
                </li>               
                <li class="px-2 py-2 flex px-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/channel.png" class="w-5 h-5 "> 
                    <span class="text-sm normal-case ml-2">Your channel</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/history.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2">History</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/playlist.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2">Playlists</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/video.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Your videos</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/later.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Watch later</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/liked.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Liked videos</span>
                </li>
            </ul>
        </div>
    <div class="mt-1">
            <ul class="border-b border-gray-300 pb-2 items-center">
                <li class="flex px-2 py-2 gap-1 block">
                    <span class="text-base font-medium">Subscriptions</span>
                </li>               
                <li class="px-2 py-2 flex px-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/tomorrowland.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm normal-case ml-2 mt-1">Tomorrowland</span>
                    <img src="~assets/images/audio.png" class="w-6 h-5 ml-4 mt-1" />
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/mini-gear.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 mt-1 text-nowrap">Mini Gear</span>
                    <img src="~assets/images/audio.png" class="w-6 h-5 ml-11 mt-1" />
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/master.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 normal-case text-nowrap mt-1">Master the Basics</span>
                    <span class="text-blue-500 px-1 mt-0.5">&bull;</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/gadget.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 normal-case text-nowrap mt-1">Gadget Addict</span>
                    <span class="text-blue-500 px-4 ml-1.5 mt-0.5">&bull;</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/madeon.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 normal-case mt-1">Madeon</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/proximity.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 normal-case mt-1">Proximity</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/electropose.png" class="rounded-full w-7 h-7"> 
                    <span class="text-sm ml-2 normal-case mt-1">ElectroPose</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize">  
                    <img src="~assets/images/down.png" class="w-5 h-5 "> 
                     <span class="text-sm ml-2 normal-case ml-5 ">Show more</span>
                </li>
            </ul>
        </div>
        <div class="mt-1">
            <ul class="border-b border-gray-300 pb-2 items-center">
                <li class="flex px-2 py-2 gap-1 block">
                    <span class="text-base font-medium">Explore</span>
                </li>               
                <li class="px-2 py-2 flex px-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/trending.png" class="w-5 h-5 "> 
                    <span class="text-sm normal-case ml-2">Trending</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/music.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2">Music</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/movies.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case text-nowrap">Movies</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/gaming.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Gaming</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/news.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">News</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/sports.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Sports</span>
                </li>
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/explore/fashion.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Fashion & Beauty</span>
                </li>
            </ul>
        </div>
        <div class="mt-1">
            <ul class="border-b border-gray-300 pb-2 items-center">
                <li class="flex px-2 py-2 gap-1 block">
                    <span class="text-base font-medium">More from YouTube</span>
                </li>               
                <li class="px-2 py-2 flex px-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/more/premium.png" class="w-5 h-5 "> 
                    <span class="text-sm normal-case ml-2">YouTube Premium</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/more/music.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2">YouTube Music</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/more/studio.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case text-nowrap">YouTube Studio</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/more/kids.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">YouTube Kids</span>
                </li>
            </ul>
        </div>
        <div class="mt-1">
            <ul class="border-b border-gray-300 pb-2 items-center">           
                <li class="px-2 py-2 flex px-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/settings.png" class="w-5 h-5 "> 
                    <span class="text-sm normal-case ml-2">Settings</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/report.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2">Report history</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/help.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case text-nowrap">Help</span>
                </li>    
                <li class="flex px-2 py-2 hover:bg-gray-400 rounded-lg capitalize gap-1.5">
                    <img src="~assets/images/send.png" class="w-5 h-5 "> 
                    <span class="text-sm ml-2 normal-case">Send feedback</span>
                </li>
            </ul>
        </div>
        <div class="text-gray-600 text-xs font-medium mt-2 px-2">
            <ul class="space-y-0">
                <li><a href="#" class="hover:underline">About</a> <a href="#" class="hover:underline">Press</a> <a href="#" class="hover:underline">Copyright</a></li>
                <li><a href="#" class="hover:underline">Contact us</a> <a href="#" class="hover:underline">Creators</a></li>
                <li><a href="#" class="hover:underline">Advertise</a> <a href="#" class="hover:underline">Developers</a></li>
            </ul>
            <ul class="space-y-0 mt-2">
                <li><a href="#" class="hover:underline">Terms</a> <a href="#" class="hover:underline">Privacy</a> <a href="#" class="hover:underline">Policy & Safety</a></li>
                <li><a href="#" class="hover:underline">How YouTube works</a></li>
                <li><a href="#" class="hover:underline">Test new features</a></li>
            </ul>
            <p class="mt-2">Copyright detected We don't own YouTube</p>
            <p class="mt-2">&copy; 2024 Google LLC</p>
        </div>
    </div>
    </div>
</template>

