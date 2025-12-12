<script lang="ts">
  const images = [
    "/generated/image-medical-professional-at-rural-health-cli-1765528951535-0.webp",
    "/generated/image-drone-delivering-food-package-to-suburba-1765528702811-2.webp",
    "/generated/image-multiple-drones-in-organized-flight-patt-1765528705820-3.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Zipline delivery in action" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Healthcare delivery <span class="text-gray-400">100km range</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
