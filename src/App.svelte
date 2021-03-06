<script>
  import Header from "./Header.svelte";
  import Menu from "./Menu.svelte";
  import Home from "./Pages/Home.svelte";
  import Cause from "./Pages/Cause.svelte";
  import Solution from "./Pages/Solution.svelte";
  import Router from 'svelte-spa-router'
  const routes = {
    '/': Home,
    '/cause': Cause,
    '/solution': Solution,
  }
</script>
<Header />
<Menu />
<Router {routes}/>
<style>
  :global(body) {
    margin: 0;
    padding: 0;
  }
</style>
