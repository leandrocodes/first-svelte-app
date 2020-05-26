<script>
  import Navbar from './components/navbar.svelte'
  export let name
</script>

<style>
  h1 {
    color: #f53e03;
    text-align: center;
    font-weight: 100;
    text-transform: uppercase;
  }
</style>

<Navbar />
<h1>Hello {name}!</h1>
