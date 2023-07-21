<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import tailwindLogo from "./assets/tailwind.svg";
  import Counter from "./lib/Counter.svelte";
  import viteLogo from "/vite.svg";
</script>

<main>
  <div>
    <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
    <a href="https://tailwindcss.com" target="_blank" rel="noreferrer">
      <img src={tailwindLogo} class="logo tailwind" alt="TailwindCSS Logo" />
    </a>
  </div>
  <h1>Vite + Svelte + Tailwind</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer"
      >SvelteKit</a
    >, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">Click on the Vite, Svelte and Tailwind logos to learn more.</p>
</main>

<style>
  .logo {
    height: 9rem;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .logo.tailwind:hover {
    filter: drop-shadow(0 0 2em #38bdf9aa);
  }
  .read-the-docs {
    color: #888;
  }

  img {
    display: inline-block;
  }
</style>
