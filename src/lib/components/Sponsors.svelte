<script lang="ts">
  // Sponsors component
  const sponsors = [
    { name: 'McKinsey & Company', logo: 'https://logo.clearbit.com/mckinsey.com' },
    { name: 'BCG', logo: 'https://logo.clearbit.com/bcg.com' },
    { name: 'Bain & Company', logo: 'https://logo.clearbit.com/bain.com' },
    { name: 'Goldman Sachs', logo: 'https://logo.clearbit.com/goldmansachs.com' },
    { name: 'Morgan Stanley', logo: 'https://logo.clearbit.com/morganstanley.com' },
    { name: 'Bank of America', logo: 'https://logo.clearbit.com/bankofamerica.com' },
    { name: 'BNP Paribas', logo: 'https://logo.clearbit.com/bnpparibas.com' },
    { name: 'Allianz', logo: 'https://logo.clearbit.com/allianz.com' },
    { name: 'PepsiCo', logo: 'https://logo.clearbit.com/pepsico.com' },
    { name: 'Deloitte', logo: 'https://logo.clearbit.com/deloitte.com' },
    { name: 'EY', logo: 'https://logo.clearbit.com/ey.com' }
  ];
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200" id="sponsors">
  <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12 gap-6">
    <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium text-[#110F28]">Partners</h2>
    <button class="bg-[#110F28] text-white text-xs font-medium px-6 py-3 rounded-full hover:bg-opacity-90 transition-opacity">
      Become a partner
    </button>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
    <!-- Info Box -->
    <div class="bg-gray-100 p-6 rounded-sm flex flex-col justify-between min-h-[160px]">
      <p class="text-xs leading-relaxed text-[#110F28] max-w-[280px]">
        EBS Symposium connects your organization with 1,100+ ambitious students and young professionals from Europe's top universities.
      </p>
      <div class="flex justify-between items-end mt-4">
        <a href="/" class="text-xs text-primary-600 hover:underline">Partner with us</a>
        <div class="w-6 h-6 rounded-full bg-gray-300 flex items-center justify-center">
             <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-600"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
        </div>
      </div>
    </div>

    <!-- Sponsor Logos -->
    {#each sponsors as sponsor}
      <div class="bg-white border border-gray-200 flex items-center justify-center h-[160px] rounded-sm group hover:shadow-md transition-all p-8">
        <span class="text-sm font-medium text-gray-600">{sponsor.name}</span>
      </div>
    {/each}

  </div>
</section>
