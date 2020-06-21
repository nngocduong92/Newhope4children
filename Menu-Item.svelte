<script>
  export let title;
  export let url;
  function handleClick() {
    if (title === "Home") {
      url = "#";
      window.location.href = url;
    }
  }
</script>
<style></style>

<button on:click={handleClick}>
  {title}
</button>
