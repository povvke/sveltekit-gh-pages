<script>
  import {count} from "$lib/store.js"
  </script>

<div>
  {$count}
  <button on:click={() => {
      count.update((n) => n+1)
    }}>Increment</button>
</div>
