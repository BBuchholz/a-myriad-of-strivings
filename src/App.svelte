<script>
  
  import FoundlingLayout from './FoundlingLayout.svelte';

  import NavBarLayout from './NavBarLayout.svelte'; 

  import {
    passPhrase,
  } from './stores.js';

  let layoutPreference = "NavBarLayout";

  function initialize(){

    const urlParams = 
      new URLSearchParams(window.location.search);
    
    if(urlParams.has('passPhrase')){
      $passPhrase = urlParams.get('passPhrase');
      console.log('passPhrase set to: ' + $passPhrase);

    }
  }

  initialize();

</script>

<svelte:head>
  <title>A Myriad Of Services</title>
  <!-- <link rel="stylesheet" href="https://getbootstrap.com/docs/4.0/dist/css/bootstrap.min.css"> -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootswatch@4.5.2/dist/slate/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
</svelte:head>

<div class="main">
  
  <FoundlingLayout />
  
</div>
