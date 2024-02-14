<script>
  import "../app.css";
</script>

<div class="container mx-auto">
  <header class="flex flex-row justify-between my-12">
    <h1 class="text-xl">
      <strong>Jodi Shou</strong>
      <small class="text-slate-500 ml-4">Marketing Strategy & Artist Manager</small>
    </h1>
    <nav class="grid gap-4 grid-flow-col text-slate-500">
      <a href="/"><strong class="text-black">Artist Management</strong></a>
      <a href="/about">FUGA</a>
      <a href="/contact">About</a>
      <a href="">Tunes</a>
      <a href="">Mood</a>
    </nav>
  </header>
  <slot />
</div>

<!-- <style lang="postcss">
  nav.a {
    
  }
  </style> -->