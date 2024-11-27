<script>
     let loggedIn = $state(false);
     function toggleLogin() {
          loggedIn = !loggedIn;
     }
</script>

{#if loggedIn}

<button onclick={toggleLogin}>Log Out</button>
{:else}
<button onclick={toggleLogin}>Log In</button>
{/if}

<style>

</style>