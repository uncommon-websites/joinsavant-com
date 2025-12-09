<script>
  const features = [
    {
      title: "hardware lab space in sf",
      description: "6,000 sq ft of fully equipped private hardware lab in the heart of san francisco, accessible only for savant founders. this is your launchpad for the next chapter.",
      image: "https://images.unsplash.com/photo-1581093458791-9f3c3900df4b?auto=format&fit=crop&q=80&w=800"
    },
    {
      title: "demo day with deep tech vcs",
      description: "we run bi-annual demo day to speedrun your fundraise from the best in silicon valley. savant founders are already backed by sv angel, outlander ventures, afore capital, boost vc, 1517 fund and angels like naval ravikant & balaji srinivasan.",
      image: "https://images.unsplash.com/photo-1544531586-fde5298cdd40?auto=format&fit=crop&q=80&w=800"
    },
    {
      title: "deep support from repeat founders",
      description: "receive intensive office hours, hands-on support in hiring and customer intros from our team of repeat deep tech founders who have been there in the trenches.",
      image: "https://images.unsplash.com/photo-1556761175-5973dc0f32e7?auto=format&fit=crop&q=80&w=800"
    },
    {
      title: "media firepower",
      description: "we don't just tell your story — we weaponize it. from cinematic launch videos to podcast, we help you shape how the world sees you. speak at choose good quests, our annual summit, own the narrative in front of the most ambitious minds in tech.",
      image: "https://images.unsplash.com/photo-1475721027767-4d56351f96db?auto=format&fit=crop&q=80&w=800"
    }
  ];
</script>

<section class="py-24 px-6 max-w-[1400px] mx-auto">
  <div class="max-w-3xl mb-20">
    <h2 class="font-serif text-5xl md:text-6xl leading-[0.95] mb-8 text-black">
      built to power founders solving hard, underserved & necessary problems
    </h2>
    <div class="space-y-4 text-lg text-gray-600 max-w-2xl">
      <p>
        great founders choose us because we give them an unfair advantage to move faster than they otherwise could.
      </p>
      <p>
        beyond writing checks, we give founders lab space to prototype, deep technical and fundraising support, and a strong community of builders chasing good quests.
      </p>
    </div>
  </div>

  <div class="space-y-0 border-t border-gray-200">
    {#each features as feature}
      <div class="grid grid-cols-1 md:grid-cols-12 gap-8 py-12 border-b border-gray-200">
        <div class="md:col-span-4 flex flex-col justify-center pr-8">
          <h3 class="font-serif text-2xl md:text-3xl mb-4 leading-tight">{feature.title}</h3>
          <p class="text-gray-600 leading-relaxed text-sm md:text-base">
            {feature.description}
          </p>
        </div>
        <div class="md:col-span-8 h-[300px] md:h-[400px] overflow-hidden bg-gray-100">
          <img 
            src={feature.image} 
            alt={feature.title}
            class="w-full h-full object-cover hover:scale-105 transition-transform duration-700"
          />
        </div>
      </div>
    {/each}
  </div>
</section>
