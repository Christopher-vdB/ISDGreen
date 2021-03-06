<script>
    import {link} from 'svelte-spa-router'
</script>
<nav>
    <a href="/" use:link>What is Climate Change?</a>
    <a href="/cause" use:link>Is ISD Causing it?</a>
    <a href="/solution" use:link>What can ISD do?</a>
</nav>
<style>
    nav {
        display: flex;
        justify-content: space-evenly;
        padding: 0.5rem;
        background-color: black;
    }
    a {
        font-family: 'Source Sans Pro', sans-serif;
        font-size: 2rem;
        font-weight: 600;
        color: white;
        text-decoration: none;
    }
</style>