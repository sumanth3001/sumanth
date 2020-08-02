
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQEstxLzPJdQNdjY1Fz3_zaxUuBcsuVHjwtYQ&usqp=CAU');}
m.h2 {
  margin-left:25%;}
ul.sidenav {
  list-style-type: none;
  padding: 0;
  width: 20%;
  position:fixed;
  left:0;
  top:0;
  background-color: #f1f1f1;
  height: 100%;
  overflow: auto;
}

ul.sidenav li a {
  display: block;
  color: #000;
  padding: 16px 16px;
  text-decoration: none;
}
 
ul.sidenav li a.active {
  background-color: #4CAF50;
  color: white;
}

ul.sidenav li a:hover:not(.active) {
  background-color: #555;
  color: white;
}

div.content {
  margin-left: 25%;
  padding: 16px ;
  height: 1000px;
}

@media screen and (max-width: 1000px) {
  ul.sidenav {
   margin:0px 0px;
    width: 100%;
    height: auto;
    position: relative;
  }
  
  ul.sidenav li a {
  float:left;
    padding: 14px;
  }
  
  div.content {margin-left: 0;}
}

@media screen and (max-width: 400px) {
  ul.sidenav li a {
    text-align: center;
    float: none;
  }
}
</style>
</head>
<body>

<ul class="sidenav">
  <li><a class="active" href="https://sumanth3001.github.io/sumanth/">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="contacts.html">Contact</a></li>
  <li><a href="images.html">Images</a></li>
</ul>

<div class="content">
  <h2 class="m">Kulkarni Sumanth</h2>
  <p>This example use media queries to transform the sidenav to a top navigation bar when the screen size is 900px or less.</p>
  <p>We have also added a media query for screens that are 400px or less, which will vertically stack and center the navigation links.</p>
  <p>You will learn more about media queries and responsive web design later in our CSS Tutorial.</p>
  <h3>Resize the browser window to see the effect.</h3>
</div>

</body>
</html>

