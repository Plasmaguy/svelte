<script>
     let clicks = $state(0);
</script>

<h1>Click me!</h1>
<button onclick={() => clicks++}>Clicks: {clicks}</button>

<style>
h1 {
     color:green;
}
</style>