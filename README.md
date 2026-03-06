# my-valentine
A small Valentine’s Day surprise made with love ❤️
# ❤️ Happy Valentine's Day

Dear Çiçək❤️,

Out of all the repositories in the world,
you are my favorite one.

if (love == true) {
    stayTogetherForever();
}

You are the best thing that ever happened to me.

Happy Valentine's Day ❤️
<!DOCTYPE html>
<html>
<head>
<title>For You ❤️</title>

<style>
body{
background:black;
overflow:hidden;
margin:0;
}

.heart{
position:absolute;
color:red;
font-size:30px;
animation:fall 5s linear infinite;
}

@keyframes fall{
0%{transform:translateY(-10vh);}
100%{transform:translateY(110vh);}
}

h1{
position:absolute;
top:40%;
width:100%;
text-align:center;
color:white;
font-size:50px;
font-family:sans-serif;
}
</style>

</head>

<body>

<h1>I Love You ❤️</h1>

<script>
function createHeart(){
const heart=document.createElement("div");
heart.classList.add("heart");
heart.innerHTML="❤️";
heart.style.left=Math.random()*100+"vw";
heart.style.animationDuration=(Math.random()*3+2)+"s";
document.body.appendChild(heart);

setTimeout(()=>{heart.remove();},5000);
}

setInterval(createHeart,300);
</script>

</body>
</html>
