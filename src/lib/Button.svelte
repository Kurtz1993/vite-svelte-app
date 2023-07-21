<script lang="ts">
  export let text: string;
  export let type: HTMLButtonElement["type"];
</script>

<button class="" {type} on:click>{text}</button>

<style lang="postcss">
  button {
    @apply font-medium rounded-lg py-2 px-4 bg-[#1a1a1a] border border-transparent hover:border-indigo-500 focus:focus-visible:outline-4 transition-colors;
  }
</style>
