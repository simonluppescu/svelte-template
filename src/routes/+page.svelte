<script>
  import Counter from "./Counter.svelte";
  import Message from "./Message.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte template" />
</svelte:head>

<section class="container mx-auto">
  <h2>This is the home page</h2>

  <Message msg="This is a message" />

  <Counter />
</section>

<style>
  h2 {
    color: darkblue;
  }
</style>
