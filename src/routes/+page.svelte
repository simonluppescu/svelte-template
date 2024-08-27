<script>
  import Counter from "./Counter.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte template" />
</svelte:head>

<section class="container mx-auto">
  <h2>This is the home page</h2>

  <Counter />
</section>

<style>
  h2 {
    color: darkblue;
  }
</style>
