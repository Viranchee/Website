<script lang="ts">
  import Tailwind from "./Tailwind.svelte";

  export let name: string;
</script>

<main>
  <Tailwind />
  <h1 class="border-red-400 text-blue-400">Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
