---
layout: default
title: Home
description: Pursue your dream
permalink: /
order: 1
---

<div class="container">
				<img class="top" src="./images/print_icon.png" onclick="myFunction()" title="Click to Print Page">
			<header>
				<h4><a href = "./home.html">
					<img rel="favicon"  src="./images/mango.png" type="image" height="60" width="60"></a>CIS 311 Web Development</h4>
					<h6><p id="demo"></p>
				<script>
					document.getElementById("demo").innerHTML = Date();
				</script></h6>
				
			</header>
			<!--         need to implement javascript. taken code from w3. yet to be fully integrated. doesn't work yet  
 <ul class="tab">
    <li><a href="javascript:./home.html" class="tablink" onclick="openPage(event, 'Home');">Home</a></li>
    <li><a href="javascript:./aboutus.html" class="tablink" onclick="openPage(event, 'About Us');">About Us</a></li>
    <li><a href="javascript:./overview.html" class="tablink" onclick="openPage(event, 'Course Overview');">Course Overview</a></li>
    <li><a href="javascript:./work.html" class="tablink" onclick="openPage(event, 'See Our Work');">See Our Work</a></li>
  </ul>              -->
			<ul class="tab">
				<li>
					<a href="./home.html" id = "Home">Home</a>
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
				<!--                         -->
					<li>
									
					</li>
					<form id="tfnewsearch" method="get" action="http://www.google.com">
						<input type="text" class="tftextinput" name="q" size="21" maxlength="120">
						<input type="submit" value="search" class="tfbutton" title="Search Google">
					</form>
				
			</ul>
			<h1><script>countdown();</script></h1>
			<br />
			
			<aside>
				<section>
				<h2> Other Web Development pages:</h2>
				<button id= "ac" class="accordion">
					W3 Schools
				</button>
				<div class="panel">
					<p>
						W3Schools is handsdown the most commonly used site for a quick reference or tutorial on how to build a website.
						<br>
						<a href="http://www.w3schools.com/about/" class="link3">About W3Schools.com</a>
					</p>
				</div>

				<button id= "bc" class="accordion">
					Code.org
				</button>
				<div class="panel">
					<p>
						A great interactive source for learning how to code in general.
						<br>
						<a href ="https://code.org/about" class="link3"> About Code.org</a>
					</p>
				</div>

				<button id= "dc" class="accordion">
					Youtube
				</button>
				<div id="foo" class="panel">
					<p>
						We know what you're thinking, "Youtube?" Yes, Youtube. On this video site, you can pull up many tutorials on web development.
						Type in html, css, javascript, jQuery tutorial, or anything else you can think of that is related to web design and development.
						See what you come up with
						<br>
						<a href="https://www.youtube.com/watch?v=3JluqTojuME" class="link3"> A Web Development Tutorial</a>
					</p>
				</div>
				</section>
				<br />
				<br/>
				<br />
				<script>
					var acc = document.getElementsByClassName("accordion");
					var i;

					for ( i = 0; i < acc.length; i++) {
						acc[i].onclick = function() {
							this.classList.toggle("active");
							this.nextElementSibling.classList.toggle("show");
						};
					};
					function clicked() {
		alert('THANK YOU FOR SUBSCRIBING');
	};
				</script>
				  <section>
				  		<h3>Subscribe for updates</h3>
						<form name="myform"  method="post" >
						    Name: <input type="text" name="name" required><br>
						    Address: <input type="text" name="address" required="@" ><br>
						    Zip: <input type="text" name="zip" required><br>
						    Phone: <input type="text" name="phone" required  autocomplete="off"><br>
						    <input type="submit" name="submit" onsubmit="clicked()" value="Submit Survey">
						</form>
				</section>
			</aside>
			
			<article>
				<h2>Purpose</h2>
				<p>
					This site serves as an overview of the CIS 311 - Web Development class at the Virginia Military Institute.
				</p>
				<h2> Department of Computer And Information Sciences</h2>
				<p> Information, computing, and information technology play a dominant role in shaping the world and will be evermore pervasive as we progress into the 
					21st Century. Computer and information scientists design, analyze, plan, build and secure these systems. Within this broad area of design, the VMI 
					CIS program provides cadets the opportunity to experience designing computer software components and implementing software systems as well as designing
					quality testing of products. <br /><br />
					We also provide training in the securing of software systems, digital forensics and exposure to product development of online and mobile platforms. 
					The program provides a solid introduction to the general areas of CIS including programming, data base design and analysis, information retrieval, 
					information architecture, software engineering, and human computer interaction. <br /><br />
					The opportunity to accomplish advanced individual or group study under the direction of a faculty member is a required experience in a two semester capstone.
</p>

			
				&nbsp;
			</article>
		</div>

	