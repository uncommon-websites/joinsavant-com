<script>
  // Header component
</script>

<header class="fixed top-0 left-0 w-full z-50 bg-[#fdfdfc]/90 backdrop-blur-sm border-b border-black/5">
  <div class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
    <!-- Logo -->
    <a href="/" class="flex items-center gap-2 group">
      <div class="relative w-6 h-6">
        <!-- Abstract sun/star icon -->
        <svg viewBox="0 0 24 24" fill="none" class="w-full h-full text-black">
          <path d="M12 2L14.5 9.5L22 12L14.5 14.5L12 22L9.5 14.5L2 12L9.5 9.5L12 2Z" fill="currentColor" />
        </svg>
      </div>
      <span class="font-bold text-lg tracking-tight">savant</span>
    </a>

    <!-- Navigation -->
    <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#manifesto" class="hover:text-black transition-colors">manifesto</a>
      <a href="#writings" class="hover:text-black transition-colors">writings</a>
      <a href="#faq" class="hover:text-black transition-colors">faq</a>
      <a href="#conference" class="hover:text-black transition-colors">conference</a>
    </nav>

    <!-- Actions -->
    <div class="flex items-center gap-4">
      <a href="#apply" class="bg-black text-white px-5 py-2 rounded-full text-sm font-medium hover:bg-gray-800 transition-colors">
        apply
      </a>
      
      <!-- Theme Toggle Mockup -->
      <button class="w-12 h-6 bg-gray-200 rounded-full relative p-1 cursor-pointer" aria-label="Toggle theme">
        <div class="w-4 h-4 bg-white rounded-full shadow-sm"></div>
      </button>
    </div>
  </div>
</header>
