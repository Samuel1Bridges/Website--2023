<script>
    import { onMount } from 'svelte';
    const token = `ocwYBAfaFxwIHfppGg9UwjsT7iTJUguvbC4i9qK4A9g`;
    const url = `https://api.unsplash.com`;


    onMount(() =>{
        fetch(`${url}/search/photos?query=cats&client_id=`)

    })
</script>



<div class = "outerbox">
    <h1 class = "maptitle">Map of Eorzea</h1>
    <div class = "innerbox">
             <img alt = "img" src = "/map/FFXIV-Map8.jpg" class="mapimg">
    </div>
</div>

<div class = "leftad">

</div>

<div class = "rightad">

</div>

<style>
    .innerbox{
        position: absolute;
        width: 100%;
        height: 500px;
        border: 2px solid black;
    }
    
    .outerbox{
        position: absolute;
        width: 50%;
        height: 500px;
        left: 25%;
        top: 25%;
    }
    
    
    .mapimg{
        width: 100%;
        height: 100%;
    }
    
    .maptitle{
        position: absolute;
        left:40%;
        top: -65px;
        
    }
    
    .leftad{
        border: 5px solid black;
        position: absolute;
        right: 30px;
        top:200px;
        width: 200px;
        height: 600px;
    }

    .rightad{
        border: 5px solid black;
        position: relative;
        left:30px;
        top:120px;
        width: 200px;
        height: 600px;

    }
    
    </style>