<script>
  import { onMount } from "svelte";
  const token = `ocwYBAfaFxwIHfppGg9UwjsT7iTJUguvbC4i9qK4A9g`;
  const url = `https://api.unsplash.com`;

  let adimgs = [];
  onMount(() => {
    fetch(
      `${url}/search/photos?query=cats&client_id=ocwYBAfaFxwIHfppGg9UwjsT7iTJUguvbC4i9qK4A9g`
    )
      .then((res) => res.json)
      .then((data) => {
        console.log(data.results);
        adimgs = data.results;
      });
    });
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
</style>
