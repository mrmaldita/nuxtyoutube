<template>
    <!-- <div class="w-full h-10 sticky top-0 bg-white z-10">
      <div>
        <ul class="flex space-x-5 list-none p-0 m-0 font-medium text-nowrap">
            <li class="bg-gray-800 rounded-lg text-white px-2 py-1">All</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Gaming</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Music</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Mobile Legends: Bang Bang </li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Javascript</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">News</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Mixes</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Computer Science</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Motovlogs</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Playlists</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Live</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Pinoy</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Filipino cuisine</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Korean cuisines</li>
            <li class="flex hover:bg-gray-300 rounded-lg px-2 py-1">Call of Duty: Mobile</li>
            </ul>
    
        </div>
    </div> -->

    <div>
  <div class="gallery js-flickity w-10/12 h-[50px] mx-10" data-flickity='{ "autoPlay": 4000 }'>
  <!--
  <div class="gallery-cell">
  </div>-->


<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">All</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Gaming</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Music</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Mobile Legends: Bang Bang</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Javascript</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">News</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Mixes</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Computer Science</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Motovlogs</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Playlists</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Live</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Pinoy</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Filipino cuisine</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Korean cuisine</div>
<div class="gallery-cell text-black rounded-sm bg-gray-200 text-center font-semibold mx-5">Call of Duty: Mobile</div>

</div>
</div>
</template>



<style scoped>
/* external css: flickity.css */
/* 
* {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
} */

.gallery {
  background: #ffffff00;
  height:40px;
  /* border-bottom: 30px solid green; */
}

.gallery-cell {
  width: 100px;
  height: 40px;
  counter-increment: gallery-cell;
}

@media only screen and (max-width: 400px) {
  /* .gallery {
  height:370px;
}
  .gallery-cell {
    width: 290px;
    height: 370px;
    margin: 0px 10px 20px 10px;
  } */
}
</style>