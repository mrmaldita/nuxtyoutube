<template>
  <div>
    <NavBar />
    <div class="flex w-full overflow-y-auto">
      <div class="w-72">
        <SideMenu />
      </div>
      <div class="w-full">
        <div class="mt-16 pt-3">
              <div class="w-full fixed top-15 z-10">
                <Tab />
              </div>
              <div class="overflow-y-auto overflow-hidden">
                <div class="grid grid-cols-5 w-full gap-3 px-2 mt-14">
                  <div v-for="(j,i) in 10" :key="i">
                    <Video />
                  </div>
                </div>
                <div class="w-full flex items-center mb-5">
                  <img src="~assets/images/shorts-red.png" class="h-7" />
                  <span class="ml-2 font-semibold text-xl">Shorts</span>
                </div>
                <div class="grid grid-cols-7 w-full gap-3 px-2 py-2">
                  <div v-for="(j,i) in 14" :key="i">
                    <Shorts />
                  </div>
                </div>
              </div>
            </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>
