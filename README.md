# mfung
Nothing
<!DOCTYPE html>
<html>
<head>
<title>Fairy Florist</title>
<link rel = "Stylesheet" type = "Text/css" href = "final project.css" /> </link>
<link rel="Stylesheet" type="Text/css" href="bgcolor.css" /> </link>


</head>
<body style="background-color:#ffb7c5"> 
<link rel = "Stylesheet" type = "Text/css" href = "word.css" /> </link>
<p align = "Center"><img src = "picture/Logo.png" height = "250" width = "250"></p>
<br>
<link rel="Stylesheet" type="Text/css" href="pinkbg.css" /> </link>
<ul>

	<li class = "dropdown"><font size = "2">
	<a href = "store.html" class = "dropbtn"> Store </a>
	<div class = "dropdown-content">
		<a href = "News.html" target = "New Window"> News </a>
		<a href = "Stats.html"> Stats </a>
	</li>
	<li><a href = "#about"> About </a></li>
	<li><a href = "register.php"> Join Us </a></li>
	<li><a href = "pay.html"> Purchase </a></li>
	<li><a href = "login.php"> Login </a></li>
	</font>
</ul>

<a style="color:white;"> Click in the picture for more info of the flower </a><br/>
<br><br>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta content="text/html; charset=iso-8859-2" http-equiv="Content-Type">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}
</style>
</head>

<body>

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}
</style>
<body>

<h2 class="w3-center"></h2>

<div class="w3-content w3-display-container">
  <a href = "rose.php" target = "New Window"><img class="mySlides" src="picture/rose.png" style="width:100%"></a>
  <a href = "wedding.php" target = "New Window"><img class="mySlides" src="picture/wedding.png" style="width:100%"></a>
  <a href = "Gebera Bouquet.php" target = "New Window"><img class="mySlides" src="picture/whiteflower.png" style="width:100%"></a>
  <a href = "rose.html" target = "New Window"><img class="mySlides" src="picture/pinkflower.png" style="width:100%"></a>

  <button class="w3-button w3-#F5F5F5 w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-#F5F5F5 w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

<h3><a name = "about"><font color = "white"> About Us </font></a></h3>
<link rel = "Stylesheet" type = "Text/css" href = "freelancer.css" /> </link>
  <footer class="footer text-center">
    <div class="container">
      <div class="row">

        <!-- Footer Location -->
        <div class="col-lg-4 mb-5 mb-lg-0">
          <h4 class="text-uppercase mb-4">Location</h4>
          <p class="lead mb-0">2215 John Daniel Drive
            <br>Clark, MO 65243</p>
        </div>

        <!-- Footer Social Icons -->
        <div class="col-lg-4 mb-5 mb-lg-0">
          <h4 class="text-uppercase mb-4">Around the Web</h4>
          <a class="btn btn-outline-light btn-social mx-1" href="#">
            <i class="fab fa-fw fa-facebook-f"></i>
          </a>
          <a class="btn btn-outline-light btn-social mx-1" href="#">
            <i class="fab fa-fw fa-twitter"></i>
          </a>
          <a class="btn btn-outline-light btn-social mx-1" href="#">
            <i class="fab fa-fw fa-linkedin-in"></i>
          </a>
          <a class="btn btn-outline-light btn-social mx-1" href="#">
            <i class="fab fa-fw fa-dribbble"></i>
          </a>
        </div>
        <div class="col-lg-4">
          <h4 class="text-uppercase mb-4">About fairy florist</h4>
          <p class="lead mb-0">
            <a href="http://startbootstrap.com">Start Bootstrap</a>.</p>
        </div>

      </div>
    </div>
  </footer>


</table>
</body>
</html>
