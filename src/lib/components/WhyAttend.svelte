<script lang="ts">
  import { Pause, Volume2 } from 'lucide-svelte';
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-16 text-[#110F28]">Why attend</h2>

  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <!-- Left Content -->
    <div class="lg:col-span-5 flex flex-col gap-16">
      
      <!-- Item 1 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-[#110F28]">Connect with industry leaders and executives</h3>
        <p class="text-sm leading-relaxed text-gray-600">
          Hear from 45–55 renowned speakers including C-suite executives, entrepreneurs, and thought leaders from leading global companies. Gain insights into business strategy, leadership, innovation, and the trends shaping tomorrow's economy.
        </p>
      </div>

      <!-- Item 2 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-[#110F28]">Access top-tier recruiting opportunities</h3>
        <p class="text-sm leading-relaxed text-gray-600 mb-4">
          Meet recruiters from McKinsey, BCG, Bain, Goldman Sachs, Morgan Stanley, and 50+ other leading firms. Participate in speed dating sessions, workshops, and exclusive networking formats designed to accelerate your career.
        </p>
      </div>

      <!-- Item 3 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-[#110F28]">Experience diverse event formats</h3>
        <p class="text-sm leading-relaxed text-gray-600 mb-3">What's included:</p>
        <ul class="list-disc pl-5 text-sm leading-relaxed text-gray-600 space-y-1 mb-4">
          <li>Keynote speeches and panel discussions</li>
          <li>Interactive workshops and interviews</li>
          <li>Career fair with major employers</li>
          <li>Speed dating with recruiters</li>
          <li>Women in Business networking event</li>
          <li>Exclusive corporate cruise with EBS Alumni</li>
        </ul>
      </div>

      <!-- Info Box -->
      <div class="bg-gray-100 p-4 rounded-lg flex items-center justify-between group cursor-pointer hover:bg-gray-200 transition-colors">
        <div>
          <p class="text-xs font-medium text-[#110F28]">Join 1,100+ students and</p>
          <p class="text-xs font-medium text-[#110F28]">young professionals from across Europe.</p>
          <p class="text-xs text-primary-600 mt-1 group-hover:underline">View past editions</p>
        </div>
        <div class="w-6 h-6 rounded-full bg-gray-300 flex items-center justify-center">
            <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-600"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
        </div>
      </div>

      <hr class="border-gray-200" />

      <!-- Item 4 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-[#110F28]">Build lasting professional relationships</h3>
        <p class="text-sm leading-relaxed text-gray-600">
          Network with ambitious peers, corporate partners, and EBS alumni in curated settings including wine tastings, evening receptions, and exclusive events. Build connections that extend far beyond the two-day conference.
        </p>
      </div>

    </div>

    <!-- Right Content (Visual) -->
    <div class="lg:col-span-7 relative min-h-[600px] bg-[#110F28] rounded-sm overflow-hidden">
      <!-- Placeholder for abstract visual/video -->
      <div class="absolute inset-0 bg-gradient-to-br from-[#110F28] to-[#2E1153]"></div>
      
      <!-- Controls -->
      <div class="absolute bottom-6 right-6 flex gap-2">
        <button class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center text-white hover:bg-white/20 transition-colors">
          <Pause size={16} />
        </button>
        <button class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center text-white hover:bg-white/20 transition-colors">
          <Volume2 size={16} />
        </button>
      </div>
    </div>
  </div>
</section>
