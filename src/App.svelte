<script>
  import Item from "./lib/ItemCard.svelte";

  const items = ["dragon lore", "M9 brødretta", "Nova", "Nova sniper"]
</script>

<main>
  <h1>Demo</h1>
  {#each items as item}
    <Item item={item}/>
  {/each}
</main>

<style>
</style>
