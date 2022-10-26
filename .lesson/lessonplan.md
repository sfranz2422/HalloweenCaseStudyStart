```html

<!DOCTYPE html>

<html lang="en">
<head>
	<meta charset="utf-8" />
	<title>Halloween Store</title>
	<link rel="stylesheet" href="styles/main.css">
</head>

<body>

  <header>
  	<img src="images/pumpkin.gif" alt="Pumpkin" width="85">
    <h2>The Halloween Store</h2>
    <h3>For the little Goblin in all of us!</h3>
  </header>

  <main>
    <h1>Welcome to my site. Please come in and stay awhile.</h1>
    <p>I started this web site because Halloween has always been my favorite holiday. 
    	But during the last year, I started selling some of my favorite Halloween products, 
    	and they've become quite a hit.</p>
    <p>If you click on the Personal link, you can browse my favorite Halloween pictures, 
    	stories, and films. And if you join my email list, I will keep you up-to-date on 
    	all things Halloween.</p>
    <h2>Product categories</h2>
    <ul>
    	<li><a href="products/props.html">Props</a></li>
    	<li><a href="products/costumes.html">Costumes</a></li>
    	<li><a href="products/special.html">Special Effects</a></li>
    	<li><a href="products/masks.html">Masks</a></li>
    </ul>
    <h3>My guarantee</h3>
    <p>If you aren't completely satisfied with everything you buy from my site, you can return it 
    	for a full refund. <strong>No questions asked!</strong></p>					
  </main>

  <footer>
	<p>&copy; 2022 Ben Murach</p>
  </footer>
</body>
</html>
```



```css


html {
	background-image: url("../images/bats.gif");	
}
body  {
	font-family: Verdana, Arial, Helvetica, sans-serif;
	width: 800px;
	background-color: white;
	margin: 0 auto; 
	padding: 0;
	border: 3px solid black;
	box-shadow: 0 9px 18px 9px;
}
h1, h2, h3, p {
	margin: 0;
	padding: 0;
}
a {
	font-weight: bold;
	color: orange;
}
a:link, a:visited { 
    color: orange; 
}
a:hover, a:focus { 
    color: green;
}

/* Header */
header { 
    background-image: linear-gradient(45deg, white 0%, orange 75%, black 100%);
    padding: 15px; 
    border-bottom: 2px solid black; 
} 
header img { 
	float: left; 
	padding-right: 15px;  
} 
header h2 {
	font-size: 230%;
}
header h3 {
	font-size: 125%;
}

/* Main */
main {
	padding: 20px 25px 25px 25px;
}
main h1 { 
	font-size: 140%;
	margin-bottom: .5em;
}
main h1:first-letter { 
	font-size: 240%;
}
main h2 {
	font-size: 125%;
	margin: .8em 0 .5em 0;
}
main h3 {
	font-size: 110%;
	margin-bottom: .5em;
}
main p {
	margin-bottom: .5em;
}
main ul {
	margin-top: 0;
}

/* Footer */
footer { 
	border-top: 2px solid black;
	padding: 15px;
    background-image: linear-gradient(45deg, black 0%, orange 25%, white 100%);
} 
footer p {
	font-size: 90%;
	text-align: center;
}

```