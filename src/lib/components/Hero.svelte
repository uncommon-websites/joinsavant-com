<script>
  // Hero component
</script>

<section class="relative pt-32 pb-20 overflow-hidden min-h-screen flex items-center">
  <!-- Grid Background -->
  <div class="absolute inset-0 bg-grid-pattern pointer-events-none opacity-60"></div>

  <div class="max-w-[1400px] mx-auto px-6 w-full grid grid-cols-1 lg:grid-cols-2 gap-12 items-center relative z-10">
    <!-- Left Content -->
    <div class="max-w-xl">
      <h1 class="font-serif text-6xl md:text-7xl lg:text-[5.5rem] leading-[0.95] tracking-tight mb-10 text-black">
        first check into exceptional founders embarking on good quests.
      </h1>
      
      <div class="flex flex-col items-start gap-3">
        <a href="#apply" class="bg-black text-white px-8 py-3.5 rounded-full text-base font-medium hover:bg-gray-800 transition-colors inline-block">
          start your application
        </a>
        <p class="text-xs text-gray-500 font-medium tracking-wide">
          [we read every submissions on a rolling basis]
        </p>
      </div>
    </div>

    <!-- Right Image (Rocket) -->
    <div class="relative h-full flex justify-center lg:justify-end items-center">
        <!-- Placeholder for the etched rocket illustration -->
        <div class="relative w-full max-w-md aspect-[3/5] grayscale contrast-125 mix-blend-multiply">
            <img 
                src="https://images.unsplash.com/photo-1517976487492-5750f3195933?q=80&w=1000&auto=format&fit=crop" 
                alt="Rocket illustration" 
                class="object-cover w-full h-full mask-image-gradient"
                style="mask-image: linear-gradient(to bottom, black 80%, transparent 100%); -webkit-mask-image: linear-gradient(to bottom, black 80%, transparent 100%);"
            />
            <!-- Overlay to simulate the etched look/drawing style -->
            <div class="absolute inset-0 bg-[#fdfdfc] mix-blend-color"></div>
        </div>
    </div>
  </div>
</section>
