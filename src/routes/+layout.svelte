<script>
    import Nav from '$lib/nav.svelte';
</script>

<style>
    :global(body){
    background-color: rgb(46, 45, 45);
    margin: 0px;
}
</style>


<svelte:head>
    <link rel="stylesheet" href="css/main.css" />
</svelte:head>




<Nav/>

<slot/>

