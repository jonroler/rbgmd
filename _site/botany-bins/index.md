<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Chrome, Firefox OS, Opera and Vivaldi -->
	<meta name="theme-color" content="#196143">
	<!-- Windows Phone -->
	<meta name="msapplication-navbutton-color" content="#196143">
	<!-- iOS Safari -->
	<meta name="apple-mobile-web-app-status-bar-style" content="#196143">
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<title>Botany Bins</title>
    

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  <link rel="icon" type="image/png" href="/images/core/rbg-favicon-leaf-32x32.png" />
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Open+Sans" /> <!-- Font 'Open Sans' Hosted by Google -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="/CSS/summer.css?v=1"> <!-- Additional local CSS -->
  
<!-- Begin Search Bar Toggle Script-->
	<script type="text/javascript"> 
	
	$(function(){
		$(".searchbar").hide();
		
	
		
		$(".searchicon").on("click", 
			function(){
		
				if( $( ".searchbar" ).is( ":hidden" ) ) {
				
				    $(".navbutton, .searchbar").toggle(300);
				    $(".searchicon").css("background-color", "#196143");
				    
				    return;
				
				}
				
				else if ( $( ".navbutton" ).is( ":hidden" ) ) { 
					
					$(".searchbar, .navbutton").toggle(300);
					$(".searchicon").css("background-color", "transparent");
					$('.searchicon').hover(
					    function() {
					      var $this = $(this);
					      $this.data('transparent', $this.css('background-color')).css('background-color', '#196143');
					    },
					    function() {
					      var $this = $(this);
					      $this.css('background-color', $this.data('transparent'));
					    }
					); 	
					
				}
		});
	
	});
	</script>
<!-- End Search Bar Toggle Script -->
  
</head>
<body>
<!-- Begin Navbar -->
<div class="navbar-wrapper">
		
		<nav class="navbar navbar-inverse navbar-static-top" role="navigation">

		  <div id="navbarbg" class="container-fluid">
		    
		    <div id="rbgnavbar" class="container-fluid">    
		    
				<div class="navbar-header">
			      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
			        <span class="icon-bar"></span>
			        <span class="icon-bar"></span>
			        <span class="icon-bar"></span>                        
			      </button>
			      <a id="logo" class="pull-left" href="/index"><img src="/images/core/logo.png" class="hover" alt="Red Butte Garden" title="Red Butte Garden" /></a>
			    </div>
			    
			    <div class="collapse navbar-collapse" id="myNavbar">
			      
			      <ul class="nav navbar-nav">
			        
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">VISIT <span class="caret"></span></a>
			          <ul class="dropdown-menu">
						<a href="/general-info"><li>GENERAL INFO</li></a>
						<a href="/about-us"><li>ABOUT US</li></a>
			            <a href="/garden-maps"><li>GARDEN MAPS</li></a>
			            <a href="/gift-shop"><li>GIFT SHOP</li></a>
			            <a href="/free-garden-events"><li>FREE DAYS<br />&amp; EVENTS</li></a>
			            <a href="/garden-tours"><li>GARDEN TOURS</li></a>
						<a href="/taleblazer"><li>PLAY TALEBLAZER</li></a>
			            <a href="/poetry"><li>POETRY IN <br />THE GARDEN</li></a>
			            <a href="/whats-happening"><li>WHAT'S HAPPENING BLOG</li></a>
			          </ul>
			        </li>
			        
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">PLANTS &amp; GARDENS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/gardens"><li>OUR GARDENS</li></a>
			            <a href="/plant-collections"><li>PLANT COLLECTIONS</li></a>
			            <a href="http://plants.redbuttegarden.org"><li>INTERACTIVE<br/>PLANT MAP</li></a>
			            <a href="/conservation-research"><li>CONSERVATION<br />RESEARCH</li></a>
			            <a href="/gardening-in-utah"><li>GARDENING IN UTAH</li></a>
			            <a href="/whats-blooming"><li>WHAT'S BLOOMING<br /> NOW BLOG</li></a>
			          </ul>
			        </li>
					
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">EVENTS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/concerts"><li class="concert-li">OUTDOOR CONCERT SERIES</li></a>
			            <a href="/spring"><li>SPRING EVENTS</li></a>
			            <a href="/summer"><li>SUMMER EVENTS</li></a>
			            <a href="/fall"><li>FALL EVENTS</li></a>
			            <a href="/winter"><li>WINTER EVENTS</li></a>
			            <a href="/calendar"><li>EVENT CALENDAR</li></a>
			          </ul>
			        </li>
					
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">EDUCATION <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/adult-education"><li>EDUCATION &amp; WORKSHOPS<br/ >FOR ADULTS</li></a>
			            <a href="/summer-camp"><li>SUMMER CAMP</li></a>			            
			            <a href="/kids-classes"><li>KIDS CLASSES</li></a>
				        <a href="/lectures"><li>LECTURES</li></a>
			            <a href="/teachers-and-students"><li>TEACHERS & STUDENTS</li></a>
			          </ul>
			        </li>
			        
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">GET INVOLVED <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/volunteer"><li>VOLUNTEER</li></a>			          
			            <a href="https://55218.blackbaudhosting.com/55218/Annual-Gift"><li>GIVE</li></a>
			            <a href="/memberships"><li>MEMBERSHIP</li></a>
			            <a href="/current-fundraisers"><li>CURRENT FUNDRAISERS</li></a>
			            <a href="/corporate-sponsorship"><li>CORPORATE <br />SPONSORSHIP</li></a>
			            <a href="/employment"><li>EMPLOYMENT</li></a>
			          </ul>
			        </li>
		
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">PRIVATE EVENTS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/weddings-and-receptions"><li>WEDDINGS<br />&amp; RECEPTIONS</li></a>
			            <a href="/private-parties"><li>CORPORATE EVENTS <br />&amp; PRIVATE PARTIES</li></a>
			            <a href="/rental-sites"><li>RENTAL SITES</li></a>
			            <a href="/rental-availability"><li>RENTAL AVAILABILITY</li></a>
			            <a href="/rental-rates-and-catering"><li>RENTAL RATES<br />& CATERING</li></a>
			          </ul>
			        </li>
			        
			        <li class="dropdown search" id="navhide4">
			          	<span class="dropdown-toggle searchicon"><a href="/search"><img src="/images/search.png"></a></span>

			        </li>
					<br class="br-hide-lg" />
					<li class="dropdown navbutton" id="navhide1">
			        	<a class="dropdown-toggle" href="https://55218.blackbaudhosting.com/55218/Annual-Gift">GIVE</a>
			        </li>  
			           
			        <li class="dropdown navbutton" id="navhide2">
			         	 <a class="dropdown-toggle" href="/memberships">JOIN</a>
			        </li>
			        
			        <li class="dropdown navbutton" id="navhide3">
			         	 <a class="dropdown-toggle" href="/volunteer">VOLUNTEER</a>
			        </li>
			        
			      </ul>
			     
			    </div>
		    
		    </div>
		      
		  </div>
		  
		</nav>
</div>
<!-- End Navbar -->


<div id="rbgdefaultbody" class="container-fluid">
  <div class="row">
  	  <div class="col-sm-12">
        <div class="eventdivide">
	<hr>
		<div class="grid-header">BOTANY BINS</div>		
	<hr>
</div>

<br />

<div class="tan-bg">
<!-- Begin Botany Bins General Description -->

	<div class="row-fluid">
		
		<br class="br-hide-lg" />
		
		<div class="col-xs-12 ev-title-mobile">
		
			<div class="memfaqwrap hover">
				<a href="/botany-bin-reservations"><div class="volbutton green-bg">RESERVE A BIN</div></a>
			</div>
			
			<br />		
		
		</div>	
		
		<div class="col-sm-6">
			
			<h3 class="text-center green">What are Botany Bins?</h3>
			
			<center>
				<img src="/images/misc/botany-bin-01.jpg" alt="Botany Bins at Red Butte Garden" title="Botany Bins at Red Butte Garden" class="responsive" style="max-height:120px; width: auto;" />
				<img src="/images/misc/botany-bins-kids.jpg" alt="Botany Bins at Red Butte Garden" title="Botany Bins at Red Butte Garden" class="responsive" style="max-height:120px; width: auto;" />
				<img src="/images/misc/botany-bin-02.jpg" alt="Botany Bins at Red Butte Garden" title="Botany Bins at Red Butte Garden" class="responsive" style="max-height:120px; width: auto;" />
			</center>
			<br />
			
			<p class="text-center">Red Butte Garden is pleased to offer a new education outreach program for public and charter classroom teachers and community groups at <strong>NO COST!</strong> Botany Bins are teacher resource kits that contain engaging, hands-on, Utah core-curriculum aligned lesson plans, related literature, touchable specimens, posters, magnifying lenses, flower presses, and reproducible materials to be used in classrooms. The Botany Bin program is provided for free to Utah public school teachers state-wide.. Visual aids and background information make the kits easy for teachers and students alike to explore the world of plants and study the fascinating science of botany!</p>
			<p class="text-center">All Botany Bins align with Utah State Core Curriculum standards. Teachers can reserve and pick up Botany Bins at Red Butte Garden or at one of eight other locations throughout Utah. Optional teacher trainings are also offered.</p>
							
		</div>	
	
		<div class="col-sm-6">
				
			<h3 class="text-center green">Botany Bin Funding is Needed!<br />Please Make A Donation</h3>
	
			<p class="text-center">Red Butte Garden needs your help to develop new modules and maintain our current ones. We've had such great success with our Botany Bins that teachers and students are asking for more - that's where you can help. Your gift to the Botany Bin Program helps us fulfill our mission to connect people with plants and the beauty of living landscapes.</p>
			
			<p class="text-center">Help us grow this new Education Outreach Program so it can continue to be provided for free to Utah public school teachers and students. You will have the satisfaction of knowing that students statewide will receive research and inquiry-based learning that aligns with the current Utah State Core Curriculum standards, and makes science fun, engaging, and interactive.</p>
			
			<p class="text-center">For more information and to learn about Botany Bin donations and sponsorship opportunities, please contact Angela Wilcox at <span class="green bold">801-585-3813</span> or email: <a href="mailto:angela.wilcox@redbutte.utah.edu">angela.wilcox@redbutte.utah.edu</a></p>
							
		</div>
	
	</div>
	
<!-- End Botany Bins General Description -->

<!-- Begin Reserve/Fund Row -->
	<div class="row-fluid">
	
		<div class="col-sm-6">
		
			<div class="memfaqwrap hover">
				<a href="/botany-bin-reservations"><div class="volbutton green-bg">RESERVE A BIN</div></a>
			</div>
			
		</div>
		
		<br class="br-hide-lg" />
		
		<div class="col-sm-6">
		
			<div class="memfaqwrap hover">
				<a href="https://55218.blackbaudhosting.com/55218/Botany-Bins-Outreach-Program"><div class="volbutton green-bg">FUND BOTANY BINS PROGRAM</div></a>
			</div>
			
		</div>
	
	</div>	
<!-- End Reserve/Fund Row -->

<br />

</div>

<br />

<!-- Begin Botany Bin Lesson Plans -->		
<div class="row-fluid">
	
	<div class="col-sm-12">
	
		<div class="memfaqwrap hover">
			<div class="volbutton" data-target="#current-botany-bins" data-toggle="collapse">CURRENT BINS &amp; LESSON PLANS</div>
		</div>
		
		<div class="collapse panel-border" id="current-botany-bins">
			
			<br />
			
			<!-- Begin Ethnobotany Bin Information and Lesson Plans -->
			<div class="tan-bg">
				<div class="row-fluid">
				
				<h3 class="text-center green">Ethnobotany: People and Plants</h3>
								
					<div class="col-sm-4">
						
						<br />
						<center><img src="/images/misc/ethnobotany-bin.jpg" alt="Ethnobotany Bin" title="Ethnobotany Bin" class="responsive" style="max-width:250px;" /></center>
						
					</div>
					
					<div class="col-sm-4">
					
						<br />
						<p class="text-center">This bin is entitled “Ethnobotany: People and Plants,” a study of how people interact with plants in their environment. Lesson plans for this module are written to align with fourth grade science core, but can also be modified for other grade level science core and intended learning outcomes. Lessons are interdisciplinary and include classification, Utah biomes, Utah native plants and their use by native people and pioneers, and plant adaptations. Teachers can efficiently cover a number of other content areas in addition to science - math, language arts, social studies, fine arts – as the bins contain appealing materials and fun, hands-on activities.</p>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="text-center green">Lesson Plans</h4>
						<br />
						<ul>
							<li><a href="#">Bin Contents</a></li>
							<li><a href="#">Introduction &amp; Overview</a></li>
							<li><a href="#">Lesson 1</a></li>
							<li><a href="#">Lesson 2</a></li>
							<li><a href="#">Lesson 3</a></li>
							<li><a href="#">Lesson 4</a></li>
							<li><a href="#">Lesson 5</a></li>
							<li><a href="#">Lesson 6</a></li>
							<li><a href="#">Lesson 7</a></li>
							<li><a href="#">Lesson 8</a></li>
						</ul>
						
					</div>
					
					<div class="col-sm-12">
						<br />
						<h4 class="text-center green">Bin Reservations</h4>
						<p class="text-center">There are a total of 16 bins. Each teacher may check out one bin for a two and one-half week time period.<br /><a href="/botany-bin-reservations">CLICK HERE to reserve a Botany Bin</a></p>
					</div>					
					
				</div>
				<br />
			</div>
			<!-- End Ethnobotany Bin Information and Lesson Plans -->
			
			<br />
			
			<!-- Begin Conserving Water in the Desert Information and Lesson Plans -->
			<div class="tan-bg">
				<div class="row-fluid">
			
				<h3 class="text-center green">Conserving Water In The Desert</h3>
								
					<div class="col-sm-4">
						
						<br />
						<center><img src="/images/misc/conserving-water-bin.jpg" alt="Conserving Water in the Desert Bin" title="Conserving Water in the Desert Bin" class="responsive" style="max-width:250px;" /></center>
						
					</div>
					
					<div class="col-sm-4">
					
						<br />
						<p class="text-center">“Conserving Water in the Desert,” provides information and activities for students to explore the water resources in Utah and the Western United States. In addition, it is the intent of this program to raise awareness about the limited availability of water in our desert climate and to encourage water conservation. The lessons focus on basic water science, the sources and availability of water for human use, some of the issues surrounding human water consumption, the importance of plants in the quality of our water, and how individual citizens can become stewards of this precious resource.</p>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="text-center green">Lesson Plans</h4>
						<br />
						<ul>
							<li><a href="#">Bin Contents</a></li>
							<li><a href="#">Introduction &amp; Overview</a></li>
							<li><a href="#">Lesson 1</a></li>
							<li><a href="#">Lesson 2</a></li>
							<li><a href="#">Lesson 3</a></li>
							<li><a href="#">Lesson 4</a></li>
							<li><a href="#">Lesson 5</a></li>
							<li><a href="#">Lesson 6</a></li>
							<li><a href="#">Lesson 7</a></li>
							<li><a href="#">Lesson 8</a></li>
							<li><a href="#">Lesson 9</a></li>
							<li><a href="#">Lesson 10</a></li>
						</ul>
						
					</div>
					
					<div class="col-sm-12">
						<br />
						<h4 class="text-center green">Bin Reservations</h4>
						<p class="text-center">There are a total of 16 bins. Each teacher may check out one bin for a two and one-half week time period.<br /><a href="/botany-bin-reservations">CLICK HERE to reserve a Botany Bin</a></p>
					</div>					
					
				</div>
				<br />
			</div>
			<!-- End Conserving Water in the Desert Information and Lesson Plans -->
			
			<br />
			
			<!-- Begin Patterns and Partnerships Information and Lesson Plans -->
			<div class="tan-bg">
				<div class="row-fluid">
			
				<h3 class="text-center green">Patterns and Partnerships: An Introduction to Botany<br /><span class="red">* Coming Soon! *</span></h3>
								
					<div class="col-sm-4">
						
						<br />
						<center><img src="/images/misc/intro-to-botany-bin.jpg" alt="Patterns and Partnerships: An Introduction to Botany" title="Patterns and Partnerships: An Introduction to Botany" class="responsive" style="max-width:250px;" /></center>
						
					</div>
					
					<div class="col-sm-4">
					
						<br />
						<p class="text-center">This module is currently in development. This bin will include lessons that cover the basics of botany for beginning and advanced young botanists, and explore the captivating patterns and partnerships found in the botanical world.</p>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="text-center green">Lesson Plans <span class="red">* Coming Soon! *</span></h4>
						<br />
						<!--
						<ul>
							<li><a href="#">Bin Contents</a></li>
							<li><a href="#">Introduction &amp; Overview</a></li>
							<li><a href="#">Lesson 1</a></li>
							<li><a href="#">Lesson 2</a></li>
							<li><a href="#">Lesson 3</a></li>
							<li><a href="#">Lesson 4</a></li>
							<li><a href="#">Lesson 5</a></li>
							<li><a href="#">Lesson 6</a></li>
							<li><a href="#">Lesson 7</a></li>
							<li><a href="#">Lesson 8</a></li>
							<li><a href="#">Lesson 9</a></li>
							<li><a href="#">Lesson 10</a></li>
						</ul>
						-->
						
					</div>
					
					<div class="col-sm-12">
						<br />
						<h4 class="text-center green">Bin Reservations</h4>
						<p class="text-center">There are a total of 16 bins. Each teacher may check out one bin for a two and one-half week time period.<br /><a href="/botany-bin-reservations">CLICK HERE to reserve a Botany Bin</a></p>
					</div>					
					
				</div>
				<br />
			</div>
			<!-- End Patterns and Partnerships Information and Lesson Plans -->
			
			<br />			
			
		</div>
		
		
	</div>

</div>
<!-- End Botany Bin Lesson Plans -->

<br />

<!-- Begin Teachers Row -->
<div class="row-fluid">

	<div class="col-sm-4">
	
		<div class="memfaqwrap hover">
			<div class="volbutton green-bg" data-target="#teacher-workshops" data-toggle="collapse">TEACHER WORKSHOPS</div>
		</div>
		
		<div class="collapse panel-border" id="teacher-workshops">
		
			<div class="row-fluid">
			
				<div class="col-sm-12">
				
					<br />
								
					<p class="text-center">Botany Bin workshops are offered at different times and locations across the state. They are not mandatory, but will give teachers an opportunity to preview the Bins and explore activities in an inquiry-based, supportive environment. Scheduled workshop dates are listed below:</p>
					
					<div class="tan-bg">
						<br />
						<h5 class="text-center green">2017 Summer / Fall Workshops</h5>
						<br />
						<ul>
							<li>TBA</li>
						</ul>
						<br />
					</div>
					<br />
					
					<div class="tan-bg">
						<br />
						<h5 class="text-center green">Ethnobotany Botany Bin Workshops:</h5>
						<br />
						<ul>
							<li>Tuesday August 9, 2-4PM <br />(2 hours relicensure credit) <br />Botany Bin Workshop 61159 / Section 79801</li>
						</ul>
						<br />
					</div>
					
					<br />
					
					<div class="tan-bg">
						<br />
						<h5 class="text-center green">Conserving Water in the Desert Botany Bin Workshops
						w/partners Utah Society for Environmental Education & Project Wet:</h5>
						<br />
						<ul>
							<li>TBA</li>
						</ul>
						<br />
					</div>
					
					<br />
					
					<p class="text-center">If you have questions please email: <a href="mailto:amie.cox@redbutte.utah.edu">amie.cox@redbutte.utah.edu</a></p>
					
					<p class="text-center">Register and Track Relicensure Credit Online!
					<br /><a href="https://usbe.truenorthlogic.com/U/P/Tab/Home">https://usbe.truenorthlogic.com/U/P/Tab/Home</a></p>
								
					<br />
					
				</div>
				
			</div>
	
		</div>
		
	</div>
	
	<br class="br-hide-lg" />
	
	<div class="col-sm-4">
	
		<div class="memfaqwrap hover">
			<a href="https://redbuttegarden.formstack.com/forms/botany_bin_survey"><div class="volbutton green-bg">TEACHER ASSESSMENT SURVEY</div></a>
		</div>
		
	</div>
	
	<br class="br-hide-lg" />
		
	<div class="col-sm-4">

		<div class="memfaqwrap hover">
			<div class="volbutton green-bg" data-target="#teacher-accolades" data-toggle="collapse">TEACHER TESTIMONIALS</div>
		</div>
		
		<div class="collapse panel-border" id="teacher-accolades">
		
			<div class="row-fluid">
			
				<div class="col-sm-12">
				
					<br />
					
					<center><img src="/images/misc/teachers-01.jpg" alt="Teachers Accolades about Botany Bins" title="Teachers Accolades about Botany Bins" class="responsive" style="max-width: 300px;" /></center>
					
					<br />
					
					<div class="tan-bg">
						<br />
						<p class="text-center">“Students were fascinated by the plants and their uses. Materials coordinated with teaching about Utah environments science curriculum and our social studies curriculum unlike anything previously available for Utah teachers.”<br />
						<span class="green bold">– Falcon Ridge Elementary, West Jordan, UT</span></p>
						<br />
					</div>
					
					<br />
					
					<div class="tan-bg">
						<br />					
						<p class="text-center">“The lesson plans were so beautiful…and they filled the requirements regarding objectives. They were teacher-friendly, along with all the engaging activities for students.”<br />
						<span class="green bold">– Davis School District, Farmington, UT</span></p>
						<br />
					</div>
					
					<br />
					
					<div class="tan-bg">
						<br />						
						<p class="text-center">“I thought the bin provided so much more than what was actually in it. We were able to have so many discussions, and new lessons were created as spinoffs to what was provided.”<br />
						<span class="green bold">– Bonneville Elementary, Salt Lake City, UT</span></p>
						<br />
					</div>
					
					<br />
					
					<div class="tan-bg">
						<br />						
						<p class="text-center">“The plant materials were fabulous! Easy to use and understand. We would like to check out more bins in the future, they are enriching and provide many resources I don’t have access to.”<br />
						<span class="green bold">– Morningside Elementary, Holladay, UT</span></p>
						<br />
					</div>
					
					<br />
					
					<div class="tan-bg">
						<br />						
						<p class="text-center">“I have a student with limited writing and reading skills but he was able to demonstrate his knowledge and understanding because of the visual and hands-on demonstrations.”<br />
						<span class="green bold">– Rose Creek Elementary, Riverton, UT</span></p>
						<br />
					</div>
						
					<br />	
						
					<div class="tan-bg">
						<br />											
						<p class="text-center">“Children grow healthier, wiser, and more content when they are more fully connected throughout their childhood to the natural environment in as many educational and recreational settings as possible. These benefits are long term and significant and contribute to their future well being and the contributions they will make to the world as adults.”<br />
						<span class="green bold">– World Forum - Nature Action Collaborative for Children (NACC)</span></p>
						<br />
					</div>

					<br />
					
				</div>
				
			</div>
	
		</div>
	
	</div>
	
</div>
<!-- End Teachers Row -->

<br />

<!-- Begin Botany Bins Calendar Panel -->
<div class="row-fluid">
	
	<div class="col-sm-12">
	
		<div class="memfaqwrap hover">
			<div class="volbutton" data-target="#bb-calendar" data-toggle="collapse">BOTANY BINS CALENDAR</div>
		</div>
		
		<div class="collapse panel-border" id="bb-calendar">
			
			<br />
			
			<iframe src="https://calendar.google.com/calendar/embed?title=RBG%20-%20Botany%20Bins&amp;height=400&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=gcloud.utah.edu_s7iu7uqkfc6lads3hl37tt9lqk%40group.calendar.google.com&amp;color=%23691426&amp;ctz=America%2FDenver" style="border-width:0" width="100%" max-width="1280px" height="400px" frameborder="0" scrolling="no"></iframe>

			<br />
			
		</div>
		
	</div>
	
</div>
<!-- End Botany Bins Calendar Panel -->

<br />

    </div>
  </div>
</div>

<!-- Google Analytics Code -->

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-252478-3', 'auto');
  ga('send', 'pageview');

</script>

</body>

<!-- Begin Footer Code-->
<div id="prefooterbg">
	
	<div id="prefooter" class="container">
	
		<div class="row">
			<div id="empty1" class="col-sm-2">&nbsp;</div>
			<div class="col-sm-2"><a href="/memberships"><div class="footer-membership"></div></a></div>
			<div class="col-sm-4"><a href="https://55218.blackbaudhosting.com/55218/Annual-Gift"><div class="footer-donate"></div></a></div>
			<div class="col-sm-2"><a href="/volunteer"><div class="footer-volunteer"></div></a></div>
			<div id="empty2" class="col-sm-2">&nbsp;</div>
		</div>
		
	</div>
	
</div>

<div id="rbgfooterbg">

	<div id="rbgfooter" class="container">
	
			<br />
	
			<div id="social-media-wrapper">
				
				<ul>
					<li><a href="http://www.yelp.com/biz/red-butte-garden-and-arboretum-salt-lake-city"><div class="yelp"></div></a></li>
					<li><a href="http://www.tripadvisor.com/Attraction_Review-g60922-d269627-Reviews-Red_Butte_Garden-Salt_Lake_City_Utah.html"><div class="tripadvisor"></div></a></li>
					<li><a href="https://plus.google.com/115349740133726957245/about"><div class="googleplus"></div></a></li>
					<li><a href="https://www.facebook.com/redbutte"><div class="facebook"></div></a></li>
					<li><a href="https://instagram.com/redbuttegarden/"><div class="instagram"></div></a></li>
					<li><a href="https://twitter.com/redbuttegarden"><div class="twitter"></div></a></li>
					<li><a href="https://www.youtube.com/user/RedButteGarden"><div class="youtube"></div></a></li>
					<li><a href="http://www.redbuttegarden.org/social-media"><div class="snapchat"></div></a></li>
					<li><a href="http://www.reddit.com/r/redbuttegarden"><div class="reddit"></div></a></li>
					<li><a href="https://www.pinterest.com/redbuttegarden/"><div class="pinterest"></div></a>
				</ul>
				
			</div>
	
			<div class="space"><hr></div><div class="space"><hr></div><div class="space"><hr></div>
			
			<div class="rbgfooterlinks">
				<ul>
					<li><a href="/contact">CONTACT US</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/advisory-board">BOARD</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/local-retail-partners">LOCAL RETAIL PARTNERS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/press">PRESS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/publications">PUBLICATIONS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/general-info">INFO &amp; POLICIES</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/employment">EMPLOYMENT</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="https://redbuttegarden.formstack.com/forms/donation_request_form" target="_blank">DONATION REQUEST</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="https://55218.blackbaudhosting.com/55218/page.aspx?pid=201" target="_blank">SIGN UP FOR OUR NEWSLETTER</a></li>
				</ul>
			</div>
			
		<div class="space"><hr></div>		
		
		<div class="row">
				
			<div id="uofu" class="col-lg-2"><a href="http://www.utah.edu"><div class="uofu"></div></a></div>
			<div id="footerlogo" class="col-lg-8"><a href="http://www.redbuttegarden.org"><div class="footerlogo"></div></a></div>
			<div id="zap" class="col-lg-2"><a href="http://www.zapisyou.org"><div class="zap"></div></a></div>
			
		</div>
		<div class="space"><hr></div>
		<div class="space"><hr></div>
		<div class="row">
	
			<div id="contactinfo1" class="col-sm-12">801.525.0556 | 300 WAKARA WAY, SALT LAKE CITY, UT 84108</div>
			<div id="contactinfo2" class="col-sm-12">Copyright &copy2016 Red Butte Garden</div>	
	
		</div>
		<div class="space"><hr></div>
		
		<div class="rbgfooterlinks">
			<ul>
				<li><a href="http://www.utah.edu/nondiscrimination/">NONDISCRIMINATION & ACCESSIBILITY</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/disclaimer/">DISCLAIMER</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/privacy/">PRIVACY</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/credits.php">CREDITS & ATTRIBUTIONS</a>&nbsp;&nbsp;&nbsp;</li>
			</ul>									
		</div>
		
	</div>

</div>
<!-- End Footer Code -->
<script>

// Code to load new CSS file to change dropdown colors for different seasons

function getStylesheet() {

  	var month = new Date().getMonth() + 1;

	if ( (month == 9) || (month == 10 ) || (month == 11) ) {
		document.write("<link rel='stylesheet' href='/CSS/fall.css?v=1' type='text/css'>");
	}
	
	if ( (month == 12) || (month == 1 ) || (month == 2) ) {
		document.write("<link rel='stylesheet' href='/CSS/winter.css?v=1' type='text/css'>");
	}
	
	if ( (month == 3) || (month == 4 ) || (month == 5) ) {
		document.write("<link rel='stylesheet' href='/CSS/spring.css?v=1' type='text/css'>");
	}
	
}

getStylesheet();

</script>

<noscript><link href="CSS/summer.css" rel="stylesheet"></noscript>