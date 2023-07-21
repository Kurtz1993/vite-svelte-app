<script lang="ts">
  import Button from "./Button.svelte";

  let count: number = 0;
  function increment() {
    count += 1;
  }
</script>

<button
  on:click={increment}
  class="rounded py-2 px-4 font-medium bg-[#1a1a1a] border border-transparent hover:border-indigo-500 focus:focus-visible:outline-4 transition-colors"
>
  count is {count}
</button>
<Button text="fas" type="button" on:click={increment} />
