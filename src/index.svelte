<script>
  let text = ''
</script>

<label>
   Write something:
  <input bind:value={text}>
</label>

<p>You wrote: {text}</p>