<script>
  import CharityList from '../components/CharityList.svelte';
  import { charities } from '../data/charities.js';
  let title = 'Charity';
</script>

<div>
  <h1>{title}</h1>
  <CharityList {charities} />
</div>

<svelte:head>
  <!-- <link href  ="https://cdn.rawgit.com/kimeiga/bahunya/css/bahunya-0.1.3.css" rel="stylesheet"/> -->
</svelte:head>

<style>
  h1 {
    font-size: 2em;
    color: brown;
  }
</style>
