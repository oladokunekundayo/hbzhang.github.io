---
layout: default
title: Photo Gallery
description: Pursue your dream
order: 2
---


			<img class="top" src="./images/print_icon.png" onclick="myFunction()" title="Click to Print Page">
			<header>
			<h4><a href = "./home.html">
				<img rel="favicon"  src="./images/mango.png" type="image" height="60" width="60"></a>CIS 311 Web Development</h4>
				<h6><p id="demo"></p>
				<script>
					document.getElementById("demo").innerHTML = Date();
				</script></h6>
			</header>
			<ul class="tab">
				<li>
					<a href="./home.html" >Home</a>
				</li>
				<li>
					<a href="./aboutus.html">About Us</a>
				</li>
				<li>
					<a href="./overview.html">Course Overview</a>
				</li>
				<li>
					<a href="./work.html">See Our Work</a>
				</li>
				<li><img class="top" src="./images/print_icon.png" ></li>
				<form id="tfnewsearch" method="get" action="http://www.google.com">
					<input type="text" class="tftextinput" name="q" size="21" maxlength="120">
					<input type="submit" value="search" class="tfbutton" title="Search Google" title="Search Google">
				</form>

			</ul>
			<h1>
			<script>
				countdown();
			</script></h1>
			<article>

				<body>
					<h2>See Our work</h2>
					<p>
						The images displayed in this slideshow are just screenshots of some of the work we've been doing throughout the course.
					</p>
					<br>
					<img class="mySlides fade" src="./images/example1.jpg" style="width:500px; height:400px;">
					<img class="mySlides fade" src="./images/example2.jpg" style="width:500px; height:400px;">
					<img class="mySlides fade" src="./images/example3.jpg" style="width:500px; height:400px;">
					<img class="mySlides fade" src="./images/example4.jpg" style="width:500px; height:400px;">
					<img class="mySlides fade" src="./images/example5.jpg" style="width:500px; height:400px;">

					<script>
						carousel();
					</script>

				</body>

			</article>

		
		