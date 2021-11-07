<script>
    export let options
    export let value
</script>

<div class="filghttype">
    <select bind:value>
      Round Trip
      <div class=""><i class="fas fa-sort-down"></i></div>
      {#each options as option}
        <option value={option.value}>{option.label}</option>
    {/each}
    </select>
  </div>