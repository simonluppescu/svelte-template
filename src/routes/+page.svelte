<script>
  import Counter from "./Counter.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte template" />
</svelte:head>

<section class="my-container">
  <h2>This is the home page</h2>

  <Counter />
</section>

<style>
  h2 {
    color: darkblue;
  }

  .my-container {
    width: 400px;
    margin: 10px auto;
  }
</style>
