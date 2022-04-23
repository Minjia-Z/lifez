<script>
    // var video = document.getElementById("LandingVideo");
    // var btn = document.getElementById("myBtn");

    // function myFunction() {
    //     if (video.paused) {
    //         video.play();
    //         btn.innerHTML = "Pause";
    //     } else {
    //         video.pause();
    //         btn.innerHTML = "Play";
    //     }
    // }
</script>

<video autoplay muted loop id="LandingVideo">
    <source src="src/party.mp4" type="video/mp4" />
</video>

<div class="content">
    <h1>Welcome to the Birthday Club!</h1>
    <p>
        Enter a 4 digit pin to enter the secret club.<br />
        (hint: your birthday in mmdd format)
    </p>
    <form>
        <label for="birthday">Secret entry pin:</label><br />
        <input type="number" id="birthday" name="birthday" /><br /><br /><br />
    </form>
    <button id="myBtn">Enter</button>
</div>

<style>
    /*@import url('https://rsms.me/inter/inter.css');*/
    @import url("https://fonts.googleapis.com/css2?family=Inter:wght@600&display=swap");
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        font-family: Arial;
        font-size: 17px;
    }

    #LandingVideo {
        position: absolute;
        z-index: -1;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    .content {
        font-family: "Inter", sans-serif;
        position: absolute;
        top: 35%;
        left: 25%;
        background: rgba(0, 0, 0, 0.6);
        color: #f1f1f1;
        width: 50%;
        padding: 40px;
        text-align: center;
        border-radius: 10px;
    }

    #myBtn {
        width: 200px;
        font-size: 18px;
        padding: 10px;
        border: none;
        background: #000;
        color: #fff;
        cursor: pointer;
    }

    #myBtn:hover {
        background: #ddd;
        color: black;
    }
</style>
