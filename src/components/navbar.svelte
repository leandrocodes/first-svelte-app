<script>
  export let navItems = ['Home', 'Projects', 'Setup', 'Contact']
</script>

<style>
  ul {
    display: flex;
    list-style-type: none;
    justify-content: flex-end;
  }
  ul li {
    margin: 0 15px;
    cursor: pointer;
  }
  ul li:hover {
    color: #f53e03;
  }
</style>

<main>
  <ul>
    {#each navItems as navItem}
      <li>{navItem}</li>
    {/each}
  </ul>
</main>
