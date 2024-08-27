<script>
  import "../app.css";
</script>

<div class="app">
  <h1>This is part of the layout.</h1>
  <a href="/">Go home</a>
  <a href="/about">Go to about</a>

  <main>
    <slot />
  </main>
</div>
