# Your_srihitha12.github.io
WEB-DEV BOOTCAMP SHAPEAI


<html>
<head>
	<title>The Rock Resume</title>
	<link href="newstyle.css" rel="stylesheet" type="text/css" />
	<style>
		*
{
	box-sizing: border-box;
}
body
{
	margin:0px;
	padding:0px;
	font:poppins;

}
#main
{
	width: 100%;
	height: 60vh;
	position: relative;
}
nav
{
	display: flex;
	justify-content: space-around;
	align-items: center;
	position: fixed;
	top:0;
	left: 0;
	width: 100%;
	background-color: white;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
	z-index: 1;
	}
	.logo img
	{
         height:45px;


	}
	.menu
	{
      list-style: none;
       display: flex;
	}

	.menu li a

{
	height: 40px;
	line-height:43px; 
	margin:3px;
	padding:0px 22px; 
	display:flex;
	font-size: 0.8em;
	text-transform: uppercase;
	font-weight: 500;
	letter-spacing: 1px;
	color: grey;

}
.hey
{
color:#39bfbd;
font-weight: 500;
font-size:0.9em;
border-bottom: 2px solid #39bfbd;
}

	ul
	{
		list-style: none;
		display: flex;
     }
	a
	{
		text-decoration: none;
	}
.image
{
	width:420px;
	height: 420px;

}

.image img
{
	width:100%;
	height:100%;
	object-fit: contain;
}
.content
{
	display: flex;
	width: 90%;
	justify-content: space-around;
	align-items: center;
	position: absolute;
	left: 45%;
	right:50%;
	transform: translate(-50%,-50%);
}
.main-text
{
	width: 500px;
}

.main-text h1
{
	font-size:3.5em;
	color: #1c3548;
	margin:0px 0px 10px 0px;
	line-height: 60px;

}
.main-text p
{
	color:grey;
}
.resume-btn
{
	width: 190px;
	height: 44px;
	display: flex;
	justify-content: center;
	align-items: center;
	color:white;
	background-color: #1db096;
	border-radius: 20px;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
}

.resume-btn:hover{
	background-color: #23cdaf;
	transition: all ease 0.2s;
}
.menu li a:hover{
	background-color: #23cdaf;
	color:white;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
	transition: all ease 0.2s;

}
	</style>

</head>
<body>
	<section id="main">
	<nav>
		<a href="#" class="logo">
		
		<img src="https://1000logos.net/wp-content/uploads/2021/04/Facebook-logo.png"   alt="the logo of project">

		</a>
		<span class="menuspace"></span>
<ul class="menu">
	<li><a href="#">Home</a></li>
	<li><a href="#">skills</a></li>
	<li><a href="#">recent</a></li>
	<li><a href="#">client</a></li>
	<li><a href="#">contact</a></li>

</ul>
<a href="#" class="hey"> <strong>Say Hi !</strong></a>
	</nav>
</section>
<section class="content">
	<div class="image">
		<img src="https://media4.s-nbcnews.com/j/newscms/2019_10/1968841/170418-facebook-f8-zuckerberg-ew-0156p_1ef15710540d3ec2bbabc02e5dba3991.fit-760w.jpg" alt="Facebook CEO ">

	</div>
	<div class="main-text">
		<h1>Hello, I am the <br> CEO </h1>
		<p>Hey, In this video I will be showing you guys, how to built website using HTML and CSS
		</p>
		<a href="#" class="resume-btn"> See My Resume</a>
</div>
</section>
</body>
</html>
