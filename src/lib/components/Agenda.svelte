<script lang="ts">
  import AgendaItem from './AgendaItem.svelte';

  const day1 = {
    date: "September 18",
    tags: ["Day 1"],
    items: [
      { time: "Morning", content: ["Registration & welcome coffee", "Opening keynote", "Panel discussion: Future of Business", "Career fair opens", "Speed dating sessions"] },
      { time: "Afternoon", content: ["Lunch networking", "Parallel workshops", "Industry leader interviews", "Career fair", "Women in Business event"] },
      { time: "Evening", title: "Welcome reception & wine tasting" }
    ]
  };

  const day2 = {
    date: "September 19",
    tags: ["Day 2"],
    items: [
      { time: "Morning", content: ["Breakfast networking", "Keynote speeches", "Panel discussions", "Speed dating sessions", "Career fair"] },
      { time: "Afternoon", content: ["Lunch at EBS campus", "Breakout sessions", "Fireside chats", "Career fair", "Closing keynote"] },
      { time: "Evening", title: "Corporate cruise with EBS Alumni" }
    ]
  };
</script>

<section class="px-6 max-w-[1400px] mx-auto">
  <AgendaItem {...day1} />
  <AgendaItem {...day2} />
</section>
