<script>
  import Greet from "$lib/Greet.svelte";
</script>

<div class="row">
  <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
    <img src="/vite.svg" class="logo vite" alt="Vite Logo" />
  </a>
  <a href="https://tauri.app" target="_blank" rel="noreferrer">
    <img src="/tauri.svg" class="logo tauri" alt="Tauri Logo" />
  </a>
  <a href="https://kit.svelte.dev" target="_blank" rel="noreferrer">
    <img src="/svelte.svg" class="logo svelte" alt="Svelte Logo" />
  </a>
</div>

<p>Click on the Tauri, Vite, and Svelte logos to learn more.</p>

<div class="row">
  <Greet />
</div>

<footer>
  <a href="/about">About my site</a>
</footer>

<style lang="scss">
  .logo {
    &.vite:hover {
      filter: drop-shadow(0 0 2em #747bff);
    }
    &.svelte:hover {
      filter: drop-shadow(0 0 2em #ff3e00);
    }
  }
</style>
