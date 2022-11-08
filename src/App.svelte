<script lang="ts">
  import Home from "./pages/Home.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Logo from "./assets/Logo256.ico";
</script>

<svelte:head>
  <link rel="icon" type="image/ico" href={Logo} />
  <meta name="description" content=
    "My personal Portfolio page, soon to be
    hosting a blog and interesting projects
    to be viewed and found!"
  >
</svelte:head>

<Navbar></Navbar>
<Home></Home>