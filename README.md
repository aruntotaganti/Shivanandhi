
<html>
<head>
<base href="images/" target="_blank">
<title>Shivanandhi(arun Totaganti web site designer) | Volunteering Organisation,</title>
<meta name="keywords" content="Shivanandhi, NGO, Youth Organisation,gajendragad">
						<meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
<meta content="text/html; charset=iso-8859-2" http-equiv="Content-Type">
<link rel="stylesheet" type="text/css" href="main.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
<style>

@media only screen and (orientation: portrait) {
  body {
    background-color: lightblue;
  }
  table{
  width:25px;
  }
}
	
p{
	color:black;
}
 
.mySlides {
	display:none;
   
   width:100%;
   }
.blue-square {
  top: 1000px;
  width: 80%;
  height: 1000px;
  
}
h1{
	text-align:center;
    border: 1px solid red;
}

.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content */
.tabcontent {
  color: white;
  display: none;
  padding: 50px;
  text-align: center;
}

hr{

border-color:white;
border-style:inset;
border-top:10px dotted black;
height:100px;
width: 30%;
}
.arun{
font-size: large;
}
/* side menu */
.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  transition: 0.5s;
  padding-top: 60px;
}

.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
  transition: 0.3s;
}

.sidenav a:hover {
  color: #f1f1f1;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

@media screen and (min-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>

<body style="background-color:#f0e3ff;">
<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#">About us </a>
  <a href="#">Services</a>
  <a href="#">Achivements</a>
  <a href="#">Contact</a>
</div>

  <div class="row">
      <div class="col-md-53" style="background-color:#2c786c;">
	<span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776; open </span>
      <p class="arun"><strong>Shivanandhi NGO group,Gajendragad</strong></p>
      </div>
    <div class="col-md-53" style="background-color:#f0e3ff;">
      <img  class="mySlides" src="images/a.jpeg" >
      <img  class="mySlides" src="images/b.jpeg"  >
      <img  class="mySlides" src="images/c.jpeg" >
 </div><br>
 
  <h3 align="center"><strong>WHO ARE WE?</strong></h3>
  <p align="center">Shivanandi is one of India largest independent youth volunteer non-profit organisations.</p>
<p align="center"><cite>Shivanandi,</cite> as a platform,In India for causes like education, environment, animals and community welfare.</p>

  <table align="center">
  <tr>
  <td><h3 style="color:blue">Group members</h3></td>
  <td><h3 style="color:blue">contact details</h3></td>
  </tr>
  <tr>
  <td>Arunkumar Totaganti</td>
  <td>8792771726</td>
  </tr>
	<tr>
  <td>Akshay Patted</td>
  <td>9480599375</td>
  </tr>
  <tr>
  <td>Bharath Noolvi</td>
  <td>8892720565</td>
  </tr>
  <tr>
  <td>Kantu</td>
  <td>8970188045</td>
  </tr>
  <tr>
  <td> kiran</td>
  <td>9964113780</td>
  </tr>
  
  <tr>
  <td> Shashi</td>
  <td>9880132016</td>
  </tr>
	<tr>
  <td> Faruk</td>
  <td>7846947443</td>
  </tr>
  
  </table>

  </div>

<script>
var myIndex = 0;
carousel();
function carousel() {
	  var i;
	  var x = document.getElementsByClassName("mySlides");
	  for (i = 0; i < x.length; i++) {
	    x[i].style.display = "none";  
	  }
	  myIndex++;
	  if (myIndex > x.length) {myIndex = 1}    
	  x[myIndex-1].style.display = "block";  
	  setTimeout(carousel, 2000); // Change image every 2 seconds
	}
	function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
	</script>
  




</body>

</html>
