<!DOCTYPE html>
<html>
<head>
<style>
#first{
	#border: 10px solid black;
	background-color: #333;
	padding: 0
}
#second{
	#border: 10px solid black;
	background-image: linear-gradient(to bottom right, lightskyblue, deepskyblue); /* Standard syntax (must be last) */
	background: url("nature.jpg") no-repeat center fixed;
  opacity: 0.8;
	padding: 250px;
}

 h1 {
 #border-style: solid;
  #border-color: #cacfca;
  color:white;
 font-family:  verdana,Courier, monospace;
 text-align: center;
vertical-align: 100px;
line-height: 50px;
}

 p{
color:white;
font-family:verdana;
font-size:20px;
text-align: center;

}

ul {
  list-style-type: none;
  margin: 0;
  #padding: 10;
  overflow: hidden;
  color: #333;

	}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}


.active {
  color: #4CAF50;
}


li a:hover {
  background: #ddd;
  color: black;
}


.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}

div.Ayush{
	background-image: linear-gradient(to bottom right, lightskyblue, deepskyblue); /* Standard syntax (must be last) */

}

</style>

<body>
	<div id="first">
		<ul>
			<li><a class="active" href="#home">Home</a></li>
			<li><a href="#news">News</a></li>
			<li><a href="#contact">Contact</a></li>
			<li><a href="#about">About</a></li>
		</ul>
	</div>


<div id = "second">
	<h1>Hello, I'm Ayush Dubey</h1>
	<p>Welcome to my website</p>
</div>

<div class="Ayush">
	<h1>This section under construction</h1>
</div>
</body>
</html>
