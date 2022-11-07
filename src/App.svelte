<script lang="ts">
  import Home from "./pages/Home.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Logo from "./assets/Logo256.ico";
</script>

<svelte:head>
  <link rel="icon" type="image/ico" href={Logo} />
</svelte:head>

<Navbar></Navbar>
<Home></Home>