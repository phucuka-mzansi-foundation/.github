<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Phucuka Mzansi Foundation</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Plus Jakarta Sans', sans-serif; }
  </style>
</head>
<body class="bg-[#0B0F17] text-white antialiased selection:bg-emerald-500 selection:text-white">

  <!-- MODERN FLOATING NAVBAR -->
  <header class="fixed top-0 left-0 right-0 z-50 px-4 sm:px-8 py-4">
    <div class="max-w-7xl mx-auto flex items-center justify-between px-6 py-3.5 bg-slate-900/75 backdrop-blur-md border border-slate-800/80 rounded-2xl shadow-2xl">
      
      <!-- Brand Logo -->
      <a href="/" class="flex items-center gap-3 group">
        <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-emerald-500 to-emerald-300 p-0.5 flex items-center justify-center shadow-lg shadow-emerald-500/20">
          <div class="w-full h-full bg-[#0B0F17] rounded-[10px] flex items-center justify-center">
            <span class="text-emerald-400 font-black text-lg">PMF</span>
          </div>
        </div>
        <span class="font-bold text-lg tracking-tight text-white group-hover:text-emerald-400 transition-colors">
          Phucuka Mzansi <span class="text-emerald-400 font-medium">Foundation</span>
        </span>
      </a>

      <!-- Desktop Links -->
      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
        <a href="#about" class="hover:text-emerald-400 transition-colors">About Us</a>
        <a href="#programs" class="hover:text-emerald-400 transition-colors">Programs & Skills</a>
        <a href="#events" class="hover:text-emerald-400 transition-colors">Events</a>
        <a href="#contact" class="hover:text-emerald-400 transition-colors">Contact</a>
      </nav>

      <!-- Action Buttons -->
      <div class="flex items-center gap-3">
        <a href="#donate" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-bold text-sm transition-all duration-200 shadow-lg shadow-emerald-500/25 hover:shadow-emerald-500/40 hover:-translate-y-0.5">
          Support Our Cause
        </a>
      </div>
    </div>
  </header>

  <!-- HERO SECTION WITH AMBIENT LIGHT & COMMUNITY IMAGE -->
  <section class="relative min-h-screen flex items-center justify-center pt-32 pb-20 px-4 sm:px-6 overflow-hidden">
    
    <!-- Background Community Visual with Gradient Vignette -->
    <div class="absolute inset-0 z-0">
      <!-- High-resolution student tech / empowerment visual -->
      <img 
        src="https://images.unsplash.com/photo-1531482615713-2afd69097998?auto=format&fit=crop&w=2000&q=80" 
        alt="African students collaborating on technology skills" 
        class="w-full h-full object-cover object-center opacity-25 scale-105 transform motion-safe:animate-pulse"
        style="animation-duration: 10s;"
      />
      <div class="absolute inset-0 bg-gradient-to-t from-[#0B0F17] via-[#0B0F17]/80 to-[#0B0F17]/60"></div>
      <div class="absolute inset-0 bg-radial-at-c from-emerald-500/15 via-transparent to-transparent"></div>
    </div>

    <!-- Hero Content Container -->
    <div class="relative z-10 max-w-4xl mx-auto text-center">
      
      <!-- Mission Pill Chip -->
      <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-emerald-950/60 border border-emerald-500/30 text-emerald-400 text-xs font-semibold uppercase tracking-wider mb-8 shadow-sm">
        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
        Empowering Communities • One Step At A Time
      </div>

      <!-- Main Catchphrase -->
      <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight text-white leading-[1.1] mb-6">
        Building Tomorrow's Leaders Through <span class="bg-clip-text text-transparent bg-gradient-to-r from-emerald-400 via-teal-300 to-emerald-200">Tech & Skills</span>
      </h1>

      <!-- Refined Mission Statement -->
      <p class="text-lg sm:text-xl text-slate-300 font-normal leading-relaxed max-w-2xl mx-auto mb-10">
        The Phucuka Mzansi Foundation is dedicated to uplifting communities across South Africa through hands-on technical education, mentorship pathways, and sustainable youth development initiatives.
      </p>

      <!-- Conversion CTA Group -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-16">
        <a href="#programs" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 rounded-xl bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-bold text-base shadow-xl shadow-emerald-500/30 hover:shadow-emerald-500/50 hover:-translate-y-0.5 transition-all">
          Explore Our Programs
          <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/>
          </svg>
        </a>
        <a href="#about" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 rounded-xl bg-slate-900/80 hover:bg-slate-800 text-white font-semibold text-base border border-slate-700 hover:border-slate-500 transition-all">
          About The Foundation
        </a>
      </div>

      <!-- Trust Metrics Bar -->
      <div class="grid grid-cols-2 md:grid-cols-3 gap-6 pt-10 border-t border-slate-800/80 max-w-3xl mx-auto">
        <div class="p-4 rounded-xl bg-slate-900/40 border border-slate-800/50">
          <div class="text-3xl font-extrabold text-white mb-1">100%</div>
          <div class="text-xs uppercase tracking-wider text-slate-400 font-semibold">Practical Skills</div>
        </div>
        <div class="p-4 rounded-xl bg-slate-900/40 border border-slate-800/50">
          <div class="text-3xl font-extrabold text-emerald-400 mb-1">Youth-Led</div>
          <div class="text-xs uppercase tracking-wider text-slate-400 font-semibold">Community Impact</div>
        </div>
        <div class="col-span-2 md:col-span-1 p-4 rounded-xl bg-slate-900/40 border border-slate-800/50">
          <div class="text-3xl font-extrabold text-white mb-1">Gauteng & Beyond</div>
          <div class="text-xs uppercase tracking-wider text-slate-400 font-semibold">South Africa Reach</div>
        </div>
      </div>

    </div>
  </section>

</body>
</html>
