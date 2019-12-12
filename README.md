<!DOCTYPE html>
<html lang="en">
<head>
<title>The End</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 1px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: ;
  width: 100%;
  height: 0px; /* only for demonstration, should be removed */
  background: #c76;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}
aside {
  float: left;
  width: 15%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}
article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}
img {
  float: left;
  width: 15%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
img ul {
  list-style-type: none;
  padding: 0;

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 90px;
  text-align: center;
  color: #c76;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>



<header>
  <h2>A</h2>
</header>
<nav>
 B
</nav>

<section>
<aside>
  <h2>C</h2>
</aside>
<article>
   <h2>B.</h2>
</article> 
<img>
    
</img>
</section>

<footer>
  <h2>E</h2>
</footer>

</body>
</html>
