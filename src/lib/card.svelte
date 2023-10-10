<script>
    import Icon from "$lib/race-images/hyur.png"
 </script>
<style>


    /* Grid css*/
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
        grid-template-columns: 25% 25% 25% 25%;
    }
    
    .parent3
    {
        grid-template-columns: 25% 25% 25% 25%;
    }
    .parent4
    {
        grid-template-columns: 1fr 1fr 1fr;
    }
    
    /* card fliping css*/
    .overlay 
    {
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
    .overlay:target 
    {
        visibility: visible;
        opacity: 1;
    }

    .popup
    {
        margin: 70px auto;
        padding: 20px;
        background: #fff;
        border-radius: 5px;
        width: 30%;
        position: relative;
        transition: all 5s ease-in-out;
    }

    .popup h2 
    {
        margin-top: 0;
        color: #333;
        font-family: Tahoma, Arial, sans-serif;
    }
    .popup .close 
    {
        position: absolute;
        top: 20px;
        right: 30px;
        transition: all 200ms;
        font-size: 30px;
        font-weight: bold;
        text-decoration: none;
        color: #333;
    }




    .button
    {
        width: 100%; height: 100%;
    }

    .images
    {
        position: relative;
        width:100%;
        height: 50%;
    }

    li
    {
        list-style-type:none;
        font-size: 25;
    }



 


    @media screen and (max-width: 1100px)
    {
    .box
    {
            width: 70%;
    }
    .popup
    {
            width: 70%;
    }

    .parent
    {
        height: 25%;
        padding: 5px 10% 0px 10%;
    }

    .parent2
    {
            grid-template-columns: auto auto;
    }
    .parent3
    {
            grid-template-columns: auto auto;
    }

    .parent4
    { 
         grid-template-columns: auto auto;
    }


    .button
    {
        width: 100%;
        height: 100%;
    }

    }
    </style>
    


    <div class = "parent parent2">
        <div class = child>

            <a href="#popup1"><img alt = "Hulur races" src="/race-images/hyur.png" class = "button"/></a>
            <div id="popup1" class="overlay">
                <div class="popup">
                    <img alt = "Hulur races" src="/race-images/hyur.png" class = "images"/>
                    <h2>Hyur 'Human'</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">

                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 
                         Over the course of some one thousand years and three great migratory waves, the
                          Hyur have come to be the most populous of the civilized races in Eorzea. Compared 
                          to the others, theirs is an average physique, both in terms of height and build. The Hyur champion personal freedom 
                         and liberty, and their espousal of an eclectic variety of languages and traditions is a legacy of their diverse heritage―as
                          is their resulting lack of a unified cultural identity.

                    </div>
                </div>
            </div>

        </div>
        <div class = child>
            <a  href="#popup2"><img alt = "miqo-te" src="/race-images/miqo-te.png" class = "button"/></a>
            <div id="popup2" class="overlay">
                <div class="popup">
                    <img alt = "miqo-te" src="/race-images/miqo-te.png" class="images"/>
                    <h2>Miqo-te</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 

                    </div>
                </div>
            </div>    
        </div>
        <div class = child> 
            <a  href="#popup3"><img alt = "elezen" src="/race-images/elezen.png" class = "button"/></a>
            <div id="popup3" class="overlay">
                <div class="popup">
                    <img alt = "elezen" src="/race-images/elezen.png" class = "images"/>
                    <h2>Elezen</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 
                    </div>
                </div>
            </div>    
        </div>

        <div class = child> 
            <a X href="#popup8"><img alt = "lalafell" src="/race-images/lalafell.png" class = "button"/></a>
            <div id="popup8" class="overlay">
                <div class="popup">
                    <img alt = "lalafell" src="/race-images/lalafell.png" class = "images"/>
                    <h2>Elezen</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 

                    </div>
                </div>
            </div>   
        </div>
    </div>

    <div class = "parent parent3">
        <div class = child>
            <a  href="#popup5"><img alt = "au-ra" src="/race-images/au-rab.jpg"class = "button"/></a>
            <div id="popup5" class="overlay">
                <div class="popup">
                    <img alt = "au-ra" src="/race-images/au-rab.jpg"class = "images"/>
                    <h2>Au-ra</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: le
                        Desciption: 

                    </div>
                </div>
            </div>   
        </div>
        <div class = child>
            <a  href="#popup6"><img alt = "roegadyn" src="/race-images/roegadyn.jpg" class = "button"/></a>
            <div id="popup6" class="overlay">
                <div class="popup">
                    <img alt = "roegadyn" src="/race-images/roegadyn.jpg" class = "images"/>
                    <h2>Roegadyn</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 

                    </div>
                </div>
            </div>   
        </div>
        <div class = child>
            <a  href="#popup7"><img alt = "viera" src="/race-images/veira.jpg" class = "button"/></a>
            <div id="popup7" class="overlay">
                <div class="popup">
                    <img alt = "viera" src="/race-images/veira.jpg" class = "images"/>
                    <h2>Viera</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male / Female</li>
                         Desciption: 

                    </div>
                </div>
            </div>   
        </div>


        <div class = child> 
            <a href="#popup9"><img alt = "hrothgar" src="/race-images/hrothgarb.jpg"  class = "button" /></a>
            <div id="popup9" class="overlay">
                <div class="popup">
                    <img alt = "hrothgar" src="/race-images/hrothgarb.jpg"  class = "images" />
                    <h2>Hrothgar</h2>
                    <a class="close" href="#">&times;</a>
                    <div class="content">
                        Details:
                        <li>Homeland: </li>
                        <li>Population:</li>
                        <li>Gender: Male</li>
                         Desciption: 

                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class = "parent parent4">




    </div>