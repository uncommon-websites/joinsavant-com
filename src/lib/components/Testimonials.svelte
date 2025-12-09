<script>
  const testimonials = [
    {
      quote: "build faster than ever",
      name: "chester",
      role: "founder @droneforge",
      image: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&q=80&w=200"
    },
    {
      quote: "couldn't have raised my pre-seed without savant",
      name: "chester",
      role: "founder @droneforge",
      image: "https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&q=80&w=200"
    },
    {
      quote: "an incredibly rigorous experience",
      name: "armaan",
      role: "founder @anomaly bio",
      image: "https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&q=80&w=200"
    }
  ];
</script>

<section class="py-24 px-6 bg-[#fdfdfc]">
  <div class="max-w-[1400px] mx-auto">
    <h2 class="font-serif text-4xl md:text-5xl text-center mb-16 text-black">
      hear from our founders
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      {#each testimonials as item}
        <div class="bg-white p-8 border border-gray-100 flex flex-col justify-between h-full min-h-[240px]">
          <p class="font-medium text-xl leading-tight mb-8">
            "{item.quote}"
          </p>
          
          <div class="flex items-center gap-3">
            <img 
              src={item.image} 
              alt={item.name} 
              class="w-10 h-10 rounded-sm object-cover grayscale"
            />
            <div>
              <p class="font-bold text-sm lowercase">{item.name}</p>
              <p class="text-xs text-gray-500">{item.role}</p>
            </div>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
