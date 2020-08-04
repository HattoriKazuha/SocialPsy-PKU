<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SocialPsy PKU</title>
</head>
<body>
<h1>Welcome to participate in our study! </h1>
<p>Firstly, you have to watch the video below.</p>
<p>After watching , you can click the button below and move on.</p>

<script src="js/plyr.js"></script>
<link rel="stylesheet" href="css/plyr.css">

<h1>video</h1>
<br />
<div class="m" align="center">
    <video width="600" height="480" controls>
        <source src="video1.mp4">
        <!-- <source src="path/to/video.webm" type="video/webm">-->
        <!-- Captions are optional -->
    </video>
    <script>plyr.setup();</script>
</div>
<br />

<style>
    .button {
        display: inline-block;
        outline: none;
        cursor: pointer;
        text-align: center;
        text-decoration: none;
        font: 30px/100% Arial, Helvetica, sans-serif;
        padding:.25em 1em .275em;

        text-shadow: 0 1px 1px rgba(0,0,0,.3);
        -webkit-border-radius: .5em;
        -moz-border-radius: .5em;
        border-radius: .5em;
        -webkit-box-shadow: 0 1px 2px rgba(0,0,0,.2);
        -moz-box-shadow: 0 1px 2px rgba(0,0,0,.2);
        box-shadow: 0 1px 2px rgba(0,0,0,.2);
    }
    .button:hover {
        text-decoration: none;
    }
    .button:active {
        position: relative;
        top: 1px;
    }

</style>

<div id="btn2" align="center">
    <a href="https://bnupsych.asia.qualtrics.com/jfe/form/SV_4ZQzpqofICY6pG5">
        <button type="button" class="button">next</button>
    </a>
</div>

</body>
</html>
