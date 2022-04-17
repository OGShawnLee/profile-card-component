<script>
  import profileImage from './assets/image-victor.jpg';
</script>

<main>
  <article
    class="min-w-xs pt-22.5 p-6 | flex flex-col items-center gap-12 | bg-white rounded-xl shadow-md">
    <div class="flex flex-col items-center gap-4">
      <img
        class="h-24 w-24 min-w-24 rounded-full ring-3 ring-white"
        width="96"
        height="96"
        src={profileImage}
        alt="Victor Profile" />
      <header class="flex flex-col items-center gap-1">
        <div class="flex items-center gap-2">
          <h1 class="text-xl font-bold">Victor Crest</h1>
          <span class="text-lg text-cadet-600"> 26 </span>
        </div>
        <span class="text-gray"> London </span>
      </header>
    </div>
    <section>
      <h2 class="sr-only">Stats</h2>
      <ul class="flex gap-8">
        <li class="flex flex-col items-center">
          <span class="text-xl font-bold"> 80K </span>
          <span class="text-xs text-gray tracking-widest"> Followers </span>
        </li>
        <li class="flex flex-col items-center">
          <span class="text-xl font-bold"> 803K </span>
          <span class="text-xs text-gray tracking-widest"> Likes </span>
        </li>
        <li class="flex flex-col items-center">
          <span class="text-xl font-bold"> 1.4K </span>
          <span class="text-xs text-gray tracking-widest"> Photos </span>
        </li>
      </ul>
    </section>
  </article>
</main>

<style>
  article {
    background-image: url(./assets/bg-pattern-card.svg);
    background-repeat: no-repeat;
  }
</style>
