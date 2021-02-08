<script lang="ts">
import Body from "./Components/Body.svelte";
import Footer from "./Components/Footer.svelte";
import Header from "./Components/Header.svelte";
import Tailwind from "./Tailwind.svelte";

export let name: string;
</script>

<main class="max-w-2xl m-auto">
  <Tailwind />
  <Header {name} />
  <Body />
  <Footer />
</main>

<style>
@media (min-width: 640px) {
  main {
    max-width: none;
  }
}
</style>
