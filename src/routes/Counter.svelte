<script lang="ts">
  let count = 0;

  $: double = count * 2;
</script>

<div>
  <p>This is a count: {count}</p>
  <p>And this is doubled: {double}</p>

  <button
    class="button bg-blue-200"
    on:click={() => {
      count -= 1;
    }}
  >
    Decrement
  </button>
  <button
    class="button bg-emerald-200"
    on:click={() => {
      count += 1;
    }}
  >
    Increment
  </button>
</div>

<style lang="postcss">
  .button {
    @apply shadow rounded p-2;
  }
</style>
