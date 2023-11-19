Nav icon: <a href="Link">Nav button name</a>

theme with Nav:
body {
    background-image: url("imgs/fusion-background.png");
  }
  h1 {
    color: white;
    text-align: center;
    font-family: Arial;
  }
  
  p {
    font-family: Arial;
    font-size: 20px;
    color: white
  }
  /* Add a black background color to the top navigation */
.topnav {
  background-color: #333;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #04AA6D;
  color: white;
}

Nav bar html:
<div class="topnav">
            <a href="index.html">Home</a>
            <a href="games/Index.html">Games</a>
          </div>