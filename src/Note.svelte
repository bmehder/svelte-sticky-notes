<script>
  export let content
</script>

<textarea bind:value={content} on:blur on:dblclick />

<style>
  textarea {
    height: 200px;
    padding: 1.5rem;
    border: none;
    border-radius: 1em;
    box-shadow: 0 0 7px rgba(0, 0, 0, 0.15);
    font-family: inherit;
    font-size: 1rem;
  }
</style>
