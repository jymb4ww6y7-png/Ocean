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

/* مكان النص */

.terminal{
    padding:20px;
    color:#00ff66;
    font-size:22px;
}

/* إعدادات الأسطر */

.line,
.line2,
.line3{

    overflow:hidden;
    white-space:nowrap;
    border-right:2px solid #00ff66;
    width:0;
    display:block;

}

/* السطر الأول */

.line{

    animation:
    typing1 3s steps(20,end) forwards,
    blink .7s infinite;

}

/* السطر الثاني */

.line2{

    animation:
    typing2 3s steps(20,end) forwards,
    blink .7s infinite;

    animation-delay:3s;

}

/* السطر الثالث */

.line3{

    animation:
    typing3 4s steps(40,end) forwards,
    blink .7s infinite;

    animation-delay:6s;

}

/* تأثير الكتابة */

@keyframes typing1{

    from{
        width:0;
    }

    to{
        width:18ch;
    }

}

@keyframes typing2{

    from{
        width:0;
    }

    to{
        width:17ch;
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

/* وميض المؤشر */

@keyframes blink{

    50%{
        border-color:transparent;
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
