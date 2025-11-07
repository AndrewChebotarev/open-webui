<script>
  export let value = '';
  export let placeholder = '';
  export let language = 'text';
  export let readonly = false;
  
  function focus() {
    // stub function
  }
  
  $: console.log('CodeEditor simplified version loaded');
</script>

<textarea 
  bind:value
  placeholder={placeholder}
  readonly={readonly}
  style="width: 100%; height: 200px; padding: 8px; font-family: monospace; border: 1px solid #ccc; border-radius: 4px;"
></textarea>