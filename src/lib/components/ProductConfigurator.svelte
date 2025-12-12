<script lang="ts">
  let selectedService = 'healthcare';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Multiple services. <span class="text-gray-400">One platform.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Healthcare Delivery</h3>
      <p class="text-gray-500 text-sm">Critical medical supplies when every second counts.</p>
    </div>

    <!-- Drone Model Display -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-modern-autonomous-delivery-drone-flying--1765528699984-0.webp" class="h-[80%] object-contain" alt="Zipline drone" />
    </div>

    <!-- Service Type Buttons -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-full bg-primary-100 border-2 border-primary-500 text-primary-700 text-sm font-medium">Healthcare</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Food</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Retail</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Enterprise</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>100km range</span>
      <span>1.8kg payload</span>
      <span>128 km/h speed</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Delivering to <span class="font-bold text-gray-900">1.3M+ locations</span> globally.<br>
      Partner with us to transform your logistics. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Learn more</span>
        <span class="text-primary-600">Explore healthcare delivery</span>
      </button>
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10"/></svg>
        View coverage map ->
      </button>
    </div>
  </div>
</section>
