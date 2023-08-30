<script>
    import Icon from "$lib/race-images/hyur.png"
 </script>
<style>

    /* Grid css*/
    .perent
    {
        display: grid;
        height: 479px;
    }
    
    .child
    {
        background-color: red;
        border: 2px solid white;
        overflow: hidden;
    }
    
    .perent2
    {
        grid-template-columns: 1fr 1fr 1fr 1fr;
    }
    
    .perent3
    {
        grid-template-columns: 1fr 1fr 1fr 1fr;
    }
    
    /* card fliping css*/
    .overlay {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.7);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
}
.overlay:target {
  visibility: visible;
  opacity: 1;
}

.popup {
  margin: 70px auto;
  padding: 20px;
  background: #fff;
  border-radius: 5px;
  width: 30%;
  position: relative;
  transition: all 5s ease-in-out;
}

.popup h2 {
  margin-top: 0;
  color: #333;
  font-family: Tahoma, Arial, sans-serif;
}
.popup .close {
  position: absolute;
  top: 20px;
  right: 30px;
  transition: all 200ms;
  font-size: 30px;
  font-weight: bold;
  text-decoration: none;
  color: #333;
}
.popup .close:hover {
  color: #06D85F;
}
.popup .content {
  max-height: 30%;
  overflow: auto;
}

@media screen and (max-width: 700px){
  .box{
    width: 70%;
  }
  .popup{
    width: 70%;
  }
}
    </style>
    


    <div class = "perent perent2">
        <div class = child>
            <a class = "button" href="#popup1"><img alt = "Hulur races" src="/race-images/hyur.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup1" class="overlay">
                <div class="popup">
                    <h2>Hyur 'Human'</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>
        </div>
        <div class = child>
            <a class = "button" href="#popup2"><img alt = "miqo-te" src="/race-images/miqo-te.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup2" class="overlay">
                <div class="popup">
                    <h2>Miqo-te</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>    
        </div>
        <div class = child> 
            <a class = "button" href="#popup3"><img alt = "elezen" src="/race-images/elezen.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup3" class="overlay">
                <div class="popup">
                    <h2>Elezen</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>    
        </div>

        <div class = child> 
            <a class = "button" href="#popup4"><img alt = "lalafell" src="/race-images/lalafell.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup4" class="overlay">
                <div class="popup">
                    <h2>Elezen</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>   
        </div>
    </div>

    <div class = "perent perent3">
        <div class = child>
            <a class = "button" href="#popup5"><img alt = "au-ra" src="/race-images/au-ra.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup5" class="overlay">
                <div class="popup">
                    <h2>Au-ra</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>   
        </div>
        <div class = child>
            <a class = "button" href="#popup6"><img alt = "roegadyn" src="/race-images/roegadyn.jpg" style="width: 678px; height: 700px;"/></a>
            <div id="popup6" class="overlay">
                <div class="popup">
                    <h2>Roegadyn</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>   
        </div>
        <div class = child>
            <a class = "button" href="#popup7"><img alt = "viera" src="/race-images/viera.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup7" class="overlay">
                <div class="popup">
                    <h2>Viera</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>   
        </div>
        <div class = child> 
            <a class = "button" href="#popup7"><img alt = "hrothgar" src="/race-images/hrothgar.png" style="width: 678px; height: 700px;"/></a>
            <div id="popup7" class="overlay">
                <div class="popup">
                    <h2>Hrothgar</h2>
                    <!-- svelte-ignore a11y-invalid-attribute -->
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        god help em
                    </div>
                </div>
            </div>
        </div>
    </div>