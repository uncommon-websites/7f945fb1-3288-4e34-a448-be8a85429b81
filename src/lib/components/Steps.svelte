<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Place order",
      desc: "Order through our app or partner platform. Select your delivery location and preferred time window.",
      img: "/generated/image-happy-customer-receiving-meal-package-fr-1765528953721-1.webp"
    },
    {
      num: "02",
      title: "Drone launch",
      desc: "Our autonomous drone is loaded with your package and launches from the nearest distribution center.",
      img: "/generated/image-zipline-distribution-center-with-technic-1765528710345-5.webp"
    },
    {
      num: "03",
      title: "In flight",
      desc: "Your package travels at 128 km/h, navigating autonomously to your exact location within minutes.",
      img: "/generated/image-modern-autonomous-delivery-drone-flying--1765528699984-0.webp"
    },
    {
      num: "04",
      title: "Delivered",
      desc: "The drone precisely delivers your package and returns to base. Fast, safe, and contactless.",
      img: "/generated/image-medical-professional-at-rural-health-cli-1765528951535-0.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Get your delivery in four simple steps. In as fast as 15 minutes.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Want the details?</h3>
        <p class="text-gray-500 text-sm">Learn more about our autonomous delivery technology.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          How it works
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download fact sheet
        </button>
      </div>
    </div>
  </div>
</section>
