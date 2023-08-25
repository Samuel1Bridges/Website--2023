<script>
    import Header from '$lib/header.svelte';
    import Footer from '$lib/footer.svelte';
    import Nav from '$lib/nav.svelte';
</script>

<svelte:head>
    <link rel="stylesheet" href="css/main.css" />
</svelte:head>


<Header/>

<Nav/>

<slot/>

<Footer/>