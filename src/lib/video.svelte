<style>
    video
    {
        pointer-events: none;
        position: absolute;
        min-width: 100%;
        min-height: 100%;
        bottom: 0;
        right: 0;
        z-index: 5;
    }

    .overlay{
        position: absolute;
        width: 100%;
        height: 100%;
        background-color: rgba(0,0,0,0.6);
        bottom: 0;
        left: 0;
    }

    .inner{
        z-index: 6;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);   
    }
    h1{   
        color: white;
        font-size: 65px;
        border: 2px solid white;
        padding: 15px;
    }
</style>

<video controls autoplay muted >
    <source src="/video/final-fantasy.mp4" type="video/mp4" class = mp4v >
        Your browser does not support the video tag.
        
</video>

<div class="overlay">
    <div class="inner">
        <h1>Final Fantasy 14</h1>
    </div>
</div>

