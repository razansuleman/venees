<!DOCTYPE html>
<html>
<head>
<style>
.button {
  display: inline-block;
  border-radius: 4px;
  background-color: #DEB887;
  border: none;
  color: #DEB887;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}


input[type=button], input[type=submit], input[type=reset] {
  background-color: #DEB887;
  border: none;
  color: white;
  padding: 16px 32px;
  text-decoration: none;
  margin: 4px 2px;
  cursor: pointer;

}


</style>
  </head>
  
<title> get ur playlist</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-wide w3-padding w3-card">
    <a href="#home" class="w3-bar-item w3-button"><b>RS</b> good luck :)</a>
    <!-- Float links to the right. Hide them on small screens -->
    <div class="w3-right w3-hide-small">
     
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1500px;" id="home">
  <img class="w3-image" src="https://www.thoughtco.com/thmb/fAYpR55rUfe254T84eJY03chw-c=/3547x3547/smart/filters:no_upscale()/illustration-to-the-divine-comedy-by-dante-alighieri--abyss-of-hell---1480-1490--found-in-the-collection-of-the-biblioteca-apostolica-vaticana--486777773-5c3a03c246e0fb00016261f2.jpg" alt="Architecture" width="1500" height="800">
  <div class="w3-display-middle w3-margin-top w3-center">
    <h1 class="w3-xxlarge w3-text-white"><span class="w3-padding w3-black w3-opacity-min"><b>hey</b></span> <span class="w3-hide-small w3-text-light-grey">always answer in one word in arabic</span></h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content w3-padding" style="max-width:1564px">

  <!-- Project Section -->
  <div class="w3-container w3-padding-32" id="start">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">click here to start</h3>
  </div>

<input class="button" name="start" id="start" type="button" value="start" onclick="window.open('code92.html')" />

   
 
 

 

</body>
</html>
