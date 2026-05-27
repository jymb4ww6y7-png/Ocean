<!DOCTYPE html>
<html lang="ar">

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

    direction:rtl;
    text-align:right;

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

    border-left:2px solid #00ff66;
    border-right:none;

    width:0;

    display:block;

    margin:20px 0;

    text-shadow:
    0 0 5px #00ff66,
    0 0 10px #00ff66,
    0 0 20px #00ff66,
    0 0 40px #00ff66;

}

/* line 1 */

.line{

    animation:
    typing1 5s steps(30,end) forwards,
    blink .1s infinite;

}

/* line 2 */

.line2{

    animation:
    typing2 5s steps(30,end) forwards,
    blink .1s infinite;

    animation-delay:5s;

}

/* line 3 */

.line3{

    animation:
    typing3 5s steps(40,end) forwards,
    blink .2s infinite;

    animation-delay:10s;

}

/* line 4 */

.line4{

    animation:
    typing4 4s steps(40,end) forwards,
    blink .1s infinite;

    animation-delay:15s;

}

/* line 5 */

.line5{

    animation:
    typing5 4s steps(40,end) forwards,
    blink .1s infinite;

    animation-delay:19s;

}

/* line 6 */

.line6{

    animation:
    typing6 4s steps(20,end) forwards,
    blink .7s infinite;

    animation-delay:23s;

}

/* typing effect */

@keyframes typing1{

    from{
        width:0;
    }

    to{
        width:24ch;
    }

}

@keyframes typing2{

    from{
        width:0;
    }

    to{
        width:28ch;
    }

}

@keyframes typing3{

    from{
        width:0;
    }

    to{
        width:34ch;
    }

}

@keyframes typing4{

    from{
        width:0;
    }

    to{
        width:27ch;
    }

}

@keyframes typing5{

    from{
        width:0;
    }

    to{
        width:29ch;
    }

}

@keyframes typing6{

    from{
        width:0;
    }

    to{
        width:5ch;
    }

}

/* cursor blink */

@keyframes blink{

    50%{
        border-color:transparent;
    }

}

</style>
</head>

<body>

<div class="terminal">

<div class="line">تبعد واحسك دوم قاعد ببالي ></div>

<div class="line2">والتفت ماالقاك واحضن خيالي ></div>

<div class="line3">قلبي اليحبك موت قد مايحبك . . . ></div>

<div class="line4">مو قلبي لاوالله سميته قلبك ></div>

<div class="line5">ماعندي كل غالين بس انت غالي ></div>

<div class="line6">MMM. ></div>

</div>

<audio autoplay loop>
<source src="https://files.catbox.moe/6rj9xf.mp3" type="audio/mp3">
</audio>

</body>
</html>
