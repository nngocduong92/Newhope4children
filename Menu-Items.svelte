<script>
  import MenuItem from "./Menu-Item.svelte";

  const items = [
    {
      name: "Home",
      url: ""
    },
    {
      name: "Introduction",
      url: "introduction"
    }
  ];
</script>

<style>

</style>

{#each items as item}
  <MenuItem title={item.name} url={item.url} />
{/each}
