<script>
  import CharityList from '../components/CharityList.svelte';

  let title = 'Charity';

  let charities = ['Charity 1', 'Charity 2', 'Charity 3', 'Charity 4'];
</script>

<div>
  <h1>{title}</h1>
  <CharityList {charities} />
  <CharityList />
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
