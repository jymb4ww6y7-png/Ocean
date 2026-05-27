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
}

.terminal{
    padding:20px;
    color:#00ff66;
    font-size:22px;
}

/* lines */

.line,
.line2,
.line3,
.line4,
.line5,
.line6{

    overflow:hidden;
    white-space:nowrap;
    border-right:2px solid #00ff66;
    width:0;
    display:block;

}

/* line 1 */

.line{

    animation:
    typing1 5s steps(20,end) forwards,
    blink .1s infinite;

}

/* line 2 */

.line2{

    animation:
    typing2 5s steps(20,end) forwards,
    blink .1s infinite;

    animation-delay:3s;

}

/* line 3 */

.line3{

    animation:
    typing3 5s steps(40,end) forwards,
    blink.0.2s infinite;

    animation-delay:6s;

}

/* line 4 */

.line4{

    animation:
    typing4 4s steps(40,end) forwards,
    blink .1s infinite;

    animation-delay:10s;

}

/* line 5 */

.line5{

    animation:
    typing5 4s steps(40,end) forwards,
    blink .s infinite;

    animation-delay:14s;

}

/* line 6 */

.line6{

    animation:
    typing6 4s steps(40,end) forwards,
    blink .7s infinite;

    animation-delay:18s;

}

/* typing */

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

/* cursor */

@keyframes blink{

    50%{
        border-color:transparent;
    }

}

</style>
</head>

<body>

<div class="terminal">

<div class="line">> تبعد واحسك دوم قاعد ببالي </div>

<br>

<div class="line2">> والتفت ماالقاك واحضن خيالي</div>

<br>

<div class="line3">> قلبي اليحبك موت قد مايحبك . . .</div>

<br>

<div class="line4">> مو قلبي لاوالله سميته قلبك </div>

<br>

<div class="line5">> ماعندي كل غالين بس انت غالي </div>

<br>

<div class="line6">> MMM. </div>

</div>

<audio autoplay loop>
<source src="https://files.catbox.moe/6rj9xf.mp3" type="audio/mp3">
</audio>

</body>
</html>
