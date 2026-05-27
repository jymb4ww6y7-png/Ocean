<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ocean</title>

<style>
body{
    margin:0;
    background:black;
    overflow:hidden;
    font-family: monospace;
}

.terminal{
    padding:20px;
    color:#00ff66;
    font-size:22px;
    white-space:pre-line;
}

.line{
    overflow:hidden;
    border-right:2px solid #00ff66;
    width:0;
    animation:typing 4s steps(40,end) forwards;
}

.line2{
    overflow:hidden;
    border-right:2px solid #00ff66;
    width:0;
    animation:typing 5s steps(40,end) forwards;
    animation-delay:4s;
}

.line3{
    overflow:hidden;
    border-right:2px solid #00ff66;
    width:0;
    animation:typing 5s steps(40,end) forwards;
    animation-delay:9s;
}

@keyframes typing{
    from{
        width:0;
    }

    to{
        width:100%;
    }
}
</style>
</head>

<body>

<div class="terminal">

<div class="line">
> i'm headed home
</div>

<br>

<div class="line2">
> i told you so
</div>

<br>

<div class="line3">
> ocean eyes and empty roads . . .
</div>

</div>

<audio autoplay loop>
<source src="https://files.catbox.moe/6rj9xf.mp3" type="audio/mp3">
</audio>

</body>
</html>
