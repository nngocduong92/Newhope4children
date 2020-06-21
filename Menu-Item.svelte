<script>
  export let title;
  export let url;
  function handleClick() {
      window.location.href = url;
  }
</script>
<style></style>

<button on:click={handleClick} class="btn btn-outline-primary">
  {title}
</button>
