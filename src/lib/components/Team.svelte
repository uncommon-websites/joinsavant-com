<script>
  const team = [
    {
      name: "jeson lee",
      role: "general partner",
      image: "https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&q=80&w=400"
    },
    {
      name: "adeel zaman",
      role: "agi venture partner",
      image: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&q=80&w=400"
    },
    {
      name: "ashis ghosh",
      role: "robotics venture partner",
      image: "https://images.unsplash.com/photo-1519345182560-3f2917c472ef?auto=format&fit=crop&q=80&w=400"
    },
    {
      name: "onkar batra",
      role: "space & defense venture partner",
      image: "https://images.unsplash.com/photo-1531384441138-2736e62e0919?auto=format&fit=crop&q=80&w=400"
    }
  ];
</script>

<section class="py-24 px-6 bg-[#fdfdfc]">
  <div class="max-w-[1400px] mx-auto">
    <h2 class="font-serif text-4xl md:text-5xl text-center mb-16 max-w-2xl mx-auto leading-tight text-black">
      team of repeat founders to build and scale with you
    </h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-x-6 gap-y-12">
      {#each team as member}
        <div class="group">
          <div class="aspect-square overflow-hidden bg-gray-200 mb-4">
            <img 
              src={member.image} 
              alt={member.name} 
              class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
            />
          </div>
          <h3 class="font-bold text-lg lowercase mb-1">{member.name}</h3>
          <p class="text-sm text-gray-600 mb-3">{member.role}</p>
          <a href="#" class="text-xs text-gray-400 underline decoration-gray-300 hover:text-black hover:decoration-black transition-colors">
            read bio
          </a>
        </div>
      {/each}
    </div>
  </div>
</section>
