<script>
  export let navItems = ['Navbar', 'Home', 'Projects', 'Setup', 'Contact']
</script>

<style>

</style>

<main>
  <ul>
    {#each navItems as navItem}
      <li>{navItem}</li>
    {/each}
  </ul>
</main>
