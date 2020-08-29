<!DOCTYPE html>
<html>
<head>
<title>Dil Dhadak </title>
<link rel="stylesheet" type="text/css" href="css/style.css">
<link href="https://fonts.googleapis.com/css?family=josefin+sans&display=swap" rel="stylesheet" >
<link rel="stylesheet" href=https://animate.style/>
<style>
* {
font-family:"josefin sans",sans-serif;
margin:0; padding:0;box-sizing: border-box;}

header {width:100%; hight:100vh;
 background-image: linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.1)), url("IMG-20200331-WA0074.jpg");
background-repeat:no-repeat;
background-size:cover;}

nav{
width:100%; height:15vh;
background-color:rgba(0,0,0,0.2);
color:white;
display:flex;
justify-content:space-between;
align-items:center;}

nav .logo{width:25%;
text-align:center;}

nav .menu{
width:40%;
display:flex;
justify-content: space-around;
}

nav .menu a{
width:25%;
text-decoration:none;
color:white;
font-weight: bold;}

nav .menu a:first-child{
color:#00b894;}

main{
width:100%;
height:85vh;
display: flex;
justify-content:center;
align-items:center;
text-align:center;
color:red;}

section{}

section h3{
font-size:35px;
font-weight:300;
text-shadow:2px 2px 3px black;
letter-spacing:2px}

section h1{
margin: 35px 0 20px 0;
font-size: 55px;
font-weight: 700;
text-shadow: 2px 1px 5px black;}

section p{
font-size:25px;
word-spacing:2px;
margin-bottom:25px;
text-shadow:1px 1px 1px black;}

section a{
padding:12px 30px;
border-radius:4px;
outline: none;
text-transform:uppercase;
font-size:13px;
font-weight:700;
text-decoration:none;
latter-spacing:1px;
transition: all .5s ease;
}

section .btnone{
background:#fff;
color:#000;}

.btnone:hover{
background:#00b894;
color:white;}

section .btntwo{
background:#00b894;
color:white;}

.btntwo:hover{
background:#fff;
color:#000;
}
.change_content:after{
content:'';
animation: changetext 20s infinite linear;
color:#00b894;
}

@keyframes changetext{
0%{content:"VISHAL (kalya)";}
10%{content:"RAJU ";}
20%{content:"AMAN";}
30%{content:"NIYAZ (CHARSI)";}
40%{content:"NEHA";}
50%{content:"AKANSHA (KANCHA)";}
60%{content:"SHAKSHI";}
85%{content:"SHUBHAM";}
100%{content:"Mr. VISHAL GUPTA";}
}
.animate
</style>
</head>
<body>
<header>
<nav>
<div class="logo"> <h1 class="animate">TRUE FRIENDSHIP<h1></div>
<div class="menu">
<a href="#">HOME</a>
<a href="#">GALLARY</a>
<a href="#">CONTACT</a>
<a href="https://www.instagram.com/vishalgupta1189/" target="_blank">ABOUT US</a>
</div>
</nav>
<main><section>
<h3>You Can See Our Friendship</h3>
<h1>YOU ARE MY BEST FRIEND<span class="change_content"> </span></h1>

<p>we are TRUE FRIENDS</p>
<a href="#" class="btnone">learn more</a>
<a href="#" class="btntwo">signup here</a>
</section></main>
<marquee>hello</marquee>
 </header>

</body>
</html>
