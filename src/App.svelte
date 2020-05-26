<script>
  import Navbar from './components/navbar'
  import Logo from './components/logo'
  export let name
</script>

<style>
  header {
    display: flex;
    justify-content: space-between;
  }
  h1 {
    color: #f53e03;
    text-align: center;
    font-weight: 100;
    text-transform: uppercase;
  }
</style>

<header>
  <Logo logo={'leandrocodes'} />
  <Navbar />
</header>
<h1>Hello {name}!</h1>
