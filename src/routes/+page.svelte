<script>
     let name=$state("Jack");
     import Counter from "./Counter.svelte";
     import Login from "./Login.svelte";
     import "../app.css";
</script>

<input type="text" bind:value={name} maxlength=12>
<h1>Hi, my name is {name}</h1>
<Counter />
<Login />

<style>
h1 {
     color:red;
}
</style>