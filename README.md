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
    font-family:monospace;

    display:flex;
    justify-content:center;
    align-items:center;

    height:100vh;
}

/* terminal */

.terminal{

    color:#00ff66;
    font-size:28px;
    text-align:left;

}

/* all lines */

.line,
.line2,
.line3,
.line4,
.line5,
.line6{

    overflow:hidden;
    white-space:nowrap;

    width:0;
    display:block;

    margin:18px 0;

    border-right:2px solid #00ff66;

    text-shadow:
    0 0 5px #00ff66,
    0 0 10px #00ff66,
    0 0 20px #00ff66,
    0 0 40px #00ff66;

}

/* line 1 */

.line{

    animation:
    typing1 3s steps(20,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

}

/* line 2 */

.line2{

    animation:
    typing2 3s steps(20,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

    animation-delay:3s;

}

/* line 3 */

.line3{

    animation:
    typing3 4s steps(40,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

    animation-delay:6s;

}

/* line 4 */

.line4{

    animation:
    typing4 4s steps(40,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

    animation-delay:10s;

}

/* line 5 */

.line5{

    animation:
    typing5 4s steps(40,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

    animation-delay:14s;

}

/* line 6 */

.line6{

    animation:
    typing6 4s steps(40,end) forwards,
    glow .08s infinite,
    blink .7s infinite;

    animation-delay:18s;

}

/* typing widths */

@keyframes typing1{
    from{ width:0; }
    to{ width:18ch; }
}

@keyframes typing2{
    from{ width:0; }
    to{ width:17ch; }
}

@keyframes typing3{
    from{ width:0; }
    to{ width:34ch; }
}

@keyframes typing4{
    from{ width:0; }
    to{ width:34ch; }
}

@keyframes typing5{
    from{ width:0; }
    to{ width:34ch; }
}

@keyframes typing6{
    from{ width:0; }
    to{ width:34ch; }
}

/* cursor blink */

@keyframes blink{

    50%{
        border-color:transparent;
    }

}

/* glowing letters */

@keyframes glow{

    0%{

        text-shadow:
        0 0 5px #00ff66,
        0 0 10px #00ff66,
        0 0 20px #00ff66;

    }

    100%{

        text-shadow:
        0 0 10px #00ff66,
        0 0 20px #00ff66,
        0 0 40px #00ff66;

    }

}

</style>
</head>

<body>

<div class="terminal">

<div class="line">> i'm headed home</div>

<div class="line2">> i told you so</div>

<div class="line3">> ocean eyes and empty roads . . .</div>

<div class="line4">> your text here</div>

<div class="line5">> your text here</div>

<div class="line6">> your text here</div>

</div>

<audio autoplay loop>
<source src="https://files.catbox.moe/6rj9xf.mp3" type="audio/mp3">
</audio>

</body>
</html>
