<script>
  export let content
</script>

<article>
  <span on:click>&times</span>
  <textarea bind:value={content} on:blur />
</article>

<style>
  article {
    display: inline-flex;
    position: relative;
  }
  textarea {
    height: 300px;
    width: auto;
    padding: 1.5rem;
    border: none;
    border-radius: 1em;
    box-shadow: 0 0 7px rgba(0, 0, 0, 0.15);
    font-family: inherit;
    font-size: 1rem;
    line-height: 1.5;
  }
  span {
    position: absolute;
    top: -0.5em;
    right: -0.5em;
    width: 1.2em;
    height: 1.2em;
    font-size: 2rem;
    line-height: 2rem;
    text-align: center;
    font-weight: bold;
    background-color: #307ad5;
    color: white;
    cursor: pointer;
    transition: transform 200ms;
    border: 1px solid white;
    border-radius: 50%;
  }
  span:hover {
    transform: scale(1.2);
  }
</style>
