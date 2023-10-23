<script>
  import Item from "./lib/ItemCard.svelte";
  import demo from "./assets/demo.png";


  const items = [
    {
      description: "Dragon Lore er en snoper lissom",
      name: "Dragon Lore",
      imageSrc: demo
  }]
</script>

<main>
  <h1>Demo</h1>
  {#each items as item}
    <Item item={item}/>
  {/each}
</main>

<style>
</style>
