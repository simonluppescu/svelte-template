<script lang="ts">
  let count = 0;

  $: double = count * 2;
</script>

<div>
  <p>This is a count: {count}</p>
  <p>And this is doubled: {double}</p>

  <button
    class="button"
    on:click={() => {
      count -= 1;
    }}
  >
    Decrement
  </button>
  <button
    class="button"
    on:click={() => {
      count += 1;
    }}
  >
    Increment
  </button>
</div>

<style>
</style>
