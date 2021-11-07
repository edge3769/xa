<script>
    export let value
    export let label
    export let name = label
    export let id
    export let placeholder
</script>

<div class="">
    <label for="">{label}</label>
    <input
    {name}
    bind:value
      type="date"
      {id}
      {placeholder}
    />
  </div>