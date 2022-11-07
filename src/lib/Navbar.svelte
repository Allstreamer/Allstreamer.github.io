<script lang="ts">

</script>

<!--TODO: Impement Tab Selection-->
<nav class="navbar">
    <a href="#" class="selected">Home</a>
    <a href="#">Blog</a>
</nav>

<style>
.navbar {
    display: flex;
    justify-content: center;
    gap: 1rem;
    background-image: linear-gradient(rgba(0, 0, 0, 0.74), rgba(0, 0, 0, 0));
    padding-top: 10px;
}

a {
    font-size: 1.3rem;
    font-weight: 400;
    text-decoration: none;
    color: white;
    opacity: 80%;
    transition: 0.5s;
    transition-timing-function: ease-in;
}
a:hover {
    font-size: 1.4rem;
    opacity: 70%;
    text-decoration: none;
}

.selected {
    font-weight: 500;
    opacity: 100%;
}
</style>