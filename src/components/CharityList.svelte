<script>
  export let charities;
</script>

<div>
  <h1>Charity List</h1>
  {#if charities !== undefined}
    <ul>
      {#each charities as Charity}
        <li> {Charity.title} - {Charity.category} </li>
      {/each}
    </ul>
  {:else}
    <h5>Kosong</h5>
  {/if}
</div>
