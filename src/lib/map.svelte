<script>
  import { onMount } from "svelte";
  const token = `ocwYBAfaFxwIHfppGg9UwjsT7iTJUguvbC4i9qK4A9g`;
  const url = `https://api.unsplash.com`;

  let adimgs = [];
  onMount(() => {
    fetch(
      `${url}/search/photos?query=laptop&page=1&per_page=3&orientation=portrait&client_id=ocwYBAfaFxwIHfppGg9UwjsT7iTJUguvbC4i9qK4A9g`
    )
      .then((res) => res.json())
      .then((data) => {
        console.log(data.results);
        document.getElementById("adimageleft").style.background =
          "url(" + data["results"][1]["urls"]["regular"] + ")";
        document.getElementById("adimageright").style.background =
          "url(" + data["results"][2]["urls"]["regular"] + ")";
      });
  });
</script>

<section>
  <div class="left box">
    <a
      href="https://www.harveynorman.co.nz/apple-computers/macbook/apple-macbook-air-13-with-m1-chip-256gb-gold-2020.html?utm_source=google&utm_medium=surfaces&utm_campaign=organic-shopping&utm_content=surfaces_across_google&gclid=EAIaIQobChMIwtua2sKwggMVjcNMAh0liAo2EAQYDCABEgKD5vD_BwE"
    >
      <h2>Buy now</h2>
      <div id="adimageleft" />
    </a>
  </div>
  <div class="boxcenter">
    <h1>Map Overview of Eorzea</h1>
    <img alt="mappicture" src="/map/FFXIV-Map8.jpg" class="map" />
  </div>
  <div class="right box">
    <a
      href="https://www.pbtech.co.nz/product/NBKLEN82019/Lenovo-V15-ITL-Business-Laptop-156-FHD-Intel-i7-11?qr=GShopping&gclid=EAIaIQobChMI8f640L6wggMVVRN7Bx1aFTYKEAQYAyABEgKXovD_BwE"
    >
      <h2>Buy now</h2>
      <div id="adimageright" />
    </a>
  </div>
</section>

<style>
  h1 {
    text-decoration: underline;
    color: white;
    text-align: center;
    font-size: 30px;
  }
  h2 {
    z-index: 6;
    position: absolute;
    bottom: 5%;
    left: 40%;
    transform: translate(-50%, -50%);
    white-space: nowrap;
    text-decoration: underline;
    color: black;
    border: 2px solid black;
    font-size: 30px;
    margin-left: 10px;
  }
  #adimageleft {
    width: 100%;
    height: 100%;
  }
  #adimageright {
    width: 100%;
    height: 100%;
  }
  .right {
    justify-self: right;
    margin-right: 15px;
  }
  .left {
    justify-self: left;
    margin-left: 15px;
  }
  .box {
    position: fixed;
    border: 3px solid white;
    width: 15vh;
    height: 60vh;
    top: 20%;
  }
  .boxcenter {
    position: fixed;
    width: 80vh;
    top: 20%;
    justify-self: center;
  }
  .map {
    width: 100%;
    height: 100%;
    border: 2px solid white;
  }
  section {
    display: grid;
  }

</style>
