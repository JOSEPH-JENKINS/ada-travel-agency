<template>
  <LocomotiveScroll
    ref="scroller"
    :getted-options="{
      offset: ['30%', 0],
      direction: 'vertical',
      smooth: true,
      getSpeed: true,
      lerp: 0.1
    }"
  >
    <main class="grid grid-cols-4 sm:grid-cols-12 px-3 w-full gap-3">
      <section class="col-span-4 sm:col-span-12 h-screen w-full relative">
        <HeroHeadline />
        <div class="absolute top-1/4 w-3/4 h-96 right-0">
          <div class="relative w-full">
            <div class="h-full w-1/2 relative">
              <p class="font-sans text-base">
                We wander for distraction, but we travel for fulfillment. We live in
                a wonderful world that is full of beauty, charm and adventure. There is
                no end to the adventures we can have if only we seek them with our eyes open.
              </p>
            </div>
            <div class="absolute right-0 h-[40vh] top-0 w-1/2 bg-black">
              <img src="~/assets/img/tommy-lisbin-xr-y6Ruw7K8-unsplash.jpg" class="w-full h-full object-cover" alt="landing image">
            </div>
          </div>
        </div>
      </section>
    </main>
  </LocomotiveScroll>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
