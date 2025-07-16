<script lang="ts">
  let {count} = $props()

  const increment = () => {
    count += 1
  }
</script>

<button onclick={increment}>
  count is {count}
</button>
