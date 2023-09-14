<style>
    .parent
    {
        display: grid;
        height: 10%;
        padding: 10px 10px 20px 10px;


    }
    
    .child
    {
        border: 2px solid black;
        margin: 5px;
        
    }
    
    .parent2
    {
        grid-template-columns: 50% 50% ;
    }
    @media screen and (max-width: 1100px)
    {
        .parent2
        {
            grid-template-columns: 1fr;
        }
    }

</style>


<h1>Phyiscal Class</h1>
<div class = " parent parent2">
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Gladiator</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Marauder</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Pugilist</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Lancer</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Archer</h1>
        <h2></h2>
    </div>
</div>
<h1>Magic Class</h1>

<div class = "parent parent2">
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Thaumaturge</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Arcanist</h1>
        <h2></h2>
    </div>
    <div class = "child">
        <img alt ="" herf =""/>
        <h1>Conjurer</h1>
        <h2></h2>
    </div>
</div>
