<script lang="ts">
  import { Plus } from 'lucide-svelte';

  const faqs = [
    "Who can attend the EBS Symposium?",
    "Do I need to be an EBS student to attend?",
    "What is included in my ticket?",
    "How do I register for the conference?",
    "Are there group discounts available?",
    "Can I transfer my ticket to someone else?",
    "What should I bring to the event?",
    "How do I access the career fair and speed dating sessions?",
    "Where is the EBS Campus located and how do I get there?",
    "Who can I contact for more information?"
  ];
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200" id="faq">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium text-[#110F28]">FAQs</h2>
    </div>

    <div class="lg:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as question}
          <div class="py-5 border-b border-gray-200 flex justify-between items-center cursor-pointer group hover:bg-gray-50 transition-colors px-2 -mx-2 rounded-sm">
            <h3 class="text-sm font-medium text-[#110F28] pr-8">{question}</h3>
            <div class="text-gray-400 group-hover:text-[#110F28] transition-colors">
              <Plus size={16} />
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
