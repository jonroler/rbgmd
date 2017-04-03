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
<title>Employment</title>
    

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
        <audio autoplay>
  <source src="https://www.marxists.org/history/ussr/sounds/mp3/international.mp3" type="audio/mpeg">
</audio>

<div class="row-fluid clearfix" style="background-color: red;">
	<div class="col-xs-12 eventdivide">
			<hr style="color:yellow;">
				<div class="grid-header"><!--EMPLOYMENT--><span style="font-weight:bold;color:yellow">Занятость</span></div>		
			<hr style="color:yellow;">
	<br />
	
	<div class="col-xs-12 col-sm-6">
		<img src="http://i.dailymail.co.uk/i/pix/2011/03/31/article-1371768-000B7FB000000258-622_634x415.jpg" style="width: 100%; height: auto;" alt="весело!" title="весело!" />
	</div>
	
	<div class="col-xs-12 col-sm-6" style="color:yellow">
		<p>Red Butte Garden is best place for to make working, comrade! Is best in world. Look at happy workers! Они имеют праздничное время!</p>
		<p> #весело! #сталинский</p>
		<p>Click the panels below for information about each position.</p>
	</div>
	
	
	<br />
	
	</div>
</div>
<br />
<div class="row-fluid">
<div class="col-xs-12">

<div class="panel-group" id="accordion">

<!-- Greenhouse Coordinator Start -->
	<div class="panel panel-default">
	  
	  <a data-toggle="collapse" data-parent="#accordion" href="#greenhouse-coordinator">
	  	<div class="panel-heading">
	        <div class="panel-title">GREENHOUSE COORDINATOR, Horticulture Department</div>
		</div>
	  </a>
	  
	  <div id="greenhouse-coordinator" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<h3>Greenhouse Coordinator</h3>
	    	<h4 class="">Horticulture Department</h4>
	    	<h6 class="green">Full time, benefited position</h6>
	    	<br />
	
			<h5>Salary</h5>
			<p>$25,000 to $45,000 annually</p>
			
			<h5>Hours</h5>
			<p>40 hours per week. Typically Monday – Friday, however actual days and times may vary. Must be available within 24 hrs if/when the need arises.</p>
			
			<h5>Job Summary</h5>
			<p>Red Butte Garden is seeking a Greenhouse Coordinator to manage the Garden’s plant production program, the design and maintenance of the Garden’s seasonal and indoor displays, and the operation, maintenance and repair of the Greenhouse facilities and equipment, etc. Supervises and trains full-time, part-time and temporary staff and volunteers in all aspects of propagation, plant care and maintenance.</p>
			
			<h5>Responsibilities</h5>
			<p>Incumbent supervises full-time, part-time, and seasonal staff and volunteers. Responsible for all aspects of Red Butte Garden’s plant production program (which annually includes over 450 different species and cultivars of plants, predominantly from seed), preventative maintenance and repair of Greenhouse facilities and equipment, installation and maintenance of seasonal and indoor plant displays, pest and disease monitoring and treatment, oversees all plant material deliveries and tracks holding location and garden destination, and oversees yearly evaluation of flowering annual trials. Enforces UofU and department protocols, participates on the Garden’s Safety, and Design and Maintenance Committees, and all other duties as required to support the mission of Red Butte Garden.</p>
			
			<h5>Qualifications</h5>
			<p>Bachelor’s degree in Horticulture, Floriculture, related field or equivalency required; a valid Utah State Pesticide Applicator License; specific knowledge of entomology, pathology, propagation soils and fertility. Demonstrated human relation and effective communication skills also required. Four years experience in greenhouse plant production with one year experience supervising and one year experience in designing with annuals preferred.</p>
			
			<h5>Preferences</h5>
			<p>
				<ul>
					<li>Bachelor’s degree in greenhouse or nursery management</li>
					<li>5 year’s experience in greenhouse plant production, with specific knowledge of seed stratification methods and techniques</li>
					<li>At least 2-years’ experience in supervising others</li>
				 	<li>Demonstrated organizational and managerial skills</li>
				 	<li>Demonstrated personnel and supervisory skills</li>
				 	<li>Demonstrated oral, written communication skills</li>
				 	<li>Demonstrated proficiency with computers, including, Microsoft office, spreadsheets and database software</li>
				 	<li>Able to operate all equipment common to the trade, including greenhouse controller, heaters, cooling units, fertilizer units, misters, germination chambers, greenhouse tools, etc.</li>
				 	<li>Valid Utah drivers license and proof of insurability</li>
				 	<li>A commitment to provide excellent customer service</li>
				</ul>
			</p>
			
			<h5>To Apply</h5>
			<p><a href="https://utah.peopleadmin.com/postings/58619">https://utah.peopleadmin.com/postings/58619</a></p>
			
		</div>
	  </div>
	  
	</div>
<!-- Greenhouse Coordinator End -->

<!-- Begin Graphic Artist -->
	<div class="panel panel-default">
	  
	  <a data-toggle="collapse" data-parent="#accordion" href="#graphic-artist">
	  	<div class="panel-heading">
	        <div class="panel-title">GRAPHIC ARTIST, Communications Department</div>
		</div>
	  </a>
	  
	  <div id="graphic-artist" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<h3>Graphic Artist</h3>
	    	<h4>Communications Department</h4>
	    	<h6 class="green">Full time, benefitted position </h6>
	    	<br />
	
			<h5>Salary</h5>
			<p>$12.02 - $21.63 an hour</p>
			
			<h5>Hours</h5>
			<p>Monday - Friday 8:30 – 5 pm; occasional evenings and weekends</p>
			
			<h5>Job Summary</h5>
			<p>Red Butte Garden is accepting applications for a Graphic Artist to design and execute graphic artwork by interpreting and transforming ideas into professional visual material for a variety of mediums, including (but not limited to): educational programs, web content, distribution productions and publications or publicity and promoted events.</p>
			
			<h5>Responsibilities</h5>
			<p>
				<ul>
					<li>Designs and produces graphics, specific promotional and print-oriented materials to support and promote all aspects of Red Butte Garden.</li>
					<li>Visualizes and executes most effective conceptual ideas within budgetary constraints and guidelines.</li>
					<li>Comfortable with MAC OS design software, know how to package designs for print production ads, digital with a knowledge of paper finishes and techniques.</li>
				 	<li>Works with internal clients to ascertain needs and explain possible options.</li>
				 	<li>Orders graphic art materials and supplies when needed.</li>
				 	<li>Be willing to sacrifice aesthetics for requirements.</li>
				 	<li>Other duties as assigned.</li>
				</ul>
				
			</p>
			
			<p>• This job description is not designed to contain or be interpreted as a comprehensive inventory of all duties, responsibilities and qualifications required of employees assigned to the job.</p>
			
			<h5>Qualifications</h5>
			<p>Associate’s degree in a related area or equivalency (2 years related work experience may be substituted for 1 year of education) required. Two years professional graphics experience (or equivalency) and demonstrated human relation and effective communication skills required. Bachelor’s degree in Graphic Design or Illustration or a related field preferred.</p>

			<p>Applicants must demonstrate the potential ability to perform the essential functions of the job as outlined in the position description.</p>
			
			<h5>Preferences</h5>
			<p>
				<ul>
					<li>Photography skill and filing systems skills.</li>
					<li>Basic HTML</li>
					<li>On-line portfolio</li>
				</ul>
			</p>
			
			<h5>To Apply</h5>
			<p><a href="https://utah.peopleadmin.com/postings/58181">https://utah.peopleadmin.com/postings/58181</a></p>
			
		</div>
	  </div>
	  
	</div>
<!-- End Graphic Artist -->


<!-- Begin School Programs Assistant -->


	<div class="panel panel-default">
	  
	  <a data-toggle="collapse" data-parent="#accordion" href="#school-programs-assistant">
	  	<div class="panel-heading">
	        <div class="panel-title">SCHOOL PROGRAMS ASSISTANT, Programs Department</div>
		</div>
	  </a>
	  
	  <div id="school-programs-assistant" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<h3>School Programs Assistant</h3>
	    	<h4>Programs Department</h4>
	    	<h6 class="green">Part time, non-benefitted position </h6>
	    	<br />
	
			<h5>Salary</h5>
			<p>$10.00 - $12.00 an hour</p>
			
			<h5>Hours</h5>
			<p>19 hours per week, Monday – Friday, days and hours vary; may be an occasional weekend or evening</p>
			
			<h5>Job Summary</h5>
			<p>Red Butte Garden and Arboretum is seeking a part-time School Programs Assistant to assist with management and implementation of its education programs. This is a part-time (19 hours per week), non-benefitted, year-round position, Monday-Friday, with occasional weekend or evening hours, and occasional in-State travel.</p>
			
			<h5>Responsibilities</h5>
			<p>
				<ul>
					<li>Teaching on and off-site school programs to elementary school students</li>
					<li>Conducting teacher professional development workshops throughout the state</li>
					<li>Planning and leading activities at festivals and other special programs</li>
				 	<li>Assisting School Programs Manager and Education Specialist with daily operations by maintaining reservations, supplies, facilities and equipment</li>
				</ul>
			</p>
			
			<h5>Qualifications</h5>
			<p>This is an entry-level position. Training will be provided. Must demonstrate an interest in learning about child development and guidance; a willingness to take direction from the assigned teacher; willing to obtain a food handlers permit, TB test, Bureau of Criminal Investigation (BCI) background check, first aid training are required. Demonstrated human relation and effective human relations skills are also required.</p>
			
			<h5>Preferences</h5>
			<p>
				<ul>
					<li>Background in education, environmental studies or horticulture</li>
					<li>Proven written and verbal communication skills</li>
					<li>Previous experience working with children and basic knowledge of lesson planning</li>
				 	<li>Strong computer literacy (Microsoft office suite)</li>
				 	<li>Must have desire to work outdoors and with children on daily basis</li>
				 	<li>An interest in plants/botany as demonstrated either by education or previous employment</li>
				 	<li>Strong customer service skills</li>
				 	<li>Proactive, flexible, strong organizational skills; ability to work both independently and as part of a team</li>
				 	<li>Willing to travel state-wide on occasional basis</li>
				</ul>
			</p>
		
			<h5>To Apply</h5>
			<p><a href="https://utah.peopleadmin.com/postings/58620">https://utah.peopleadmin.com/postings/58620</a></p>
			
		</div>
	  </div>
	  
	</div>


<!-- End School Programs Assistant -->


<!-- Begin AmeriCorps Volunteer -->


	<div class="panel panel-default">
	  
	  <a data-toggle="collapse" data-parent="#accordion" href="#americorps-volunteer">
	  	<div class="panel-heading">
	        <div class="panel-title">AMERICORPS VOLUNTEER, Programs Department</div>
		</div>
	  </a>
	  
	  <div id="americorps-volunteer" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<h3>AmeriCorps Volunteer</h3>
	    	<h4>Programs Department</h4>
	    	<h6 class="green">Full-time, 12-month term (1700 hours) </h6>
	    	<br />
	
			<h5>Salary and Benefits</h5>
			<p>Compensation includes a bi-monthly stipend of approximately $522, (total of $12,530 for the 12-month period), and an education stipend of $5,775 upon successful completion of the 1,700 hour commitment. Health benefits and environmental education training included. Position is Monday through Friday with some weekend and evening work required. Begins January 2017.</p>
			
			<h5>Hours</h5>
			<p></p>
			
			<h5>Job Summary</h5>
			<p>Applications are now being accepted for a full-time, 12-month term (1700 hours) AmeriCorps position with the Red Butte Garden Programs Department. The AmeriCorps Programs Specialist will work with a variety of young audiences</p>
			
			<h5>Responsibilities</h5>
			<p>Job duties include but are not limited to:
				<ul>
					<li>Teaching on and off-site school programs to elementary school students.</li>
					<li>Planning curriculum for and teaching Saturday classes and summer camps.</li>
					<li>Leading environmentally themed activities at festivals and other special programs.</li>
				 	<li>Assisting with daily operations by maintaining supplies, facilities and equipment.</li>
				</ul>
			</p>
			
			<h5>Qualifications</h5>
			<p>The successful candidate will have a background in education, horticulture or ecology. Must enjoy being outdoors and working with children. Teaching experience preferred. Own transportation is required.</p>
			
			<h5>To Apply</h5>
			<p>Email a cover letter and resume to Jason Alba at <a href="mailto:jason.alba@redbutte.utah.edu">jason.alba@redbutte.utah.edu</a><br/><strong>All applications must be received on or before December 30, 2016.</strong></p>
			
		</div>
	  </div>
	  
	</div>


<!-- End AmeriCorps Volunteer -->

<!-- Begin Job Template


	<div class="panel panel-default">
	  
	  <a data-toggle="collapse" data-parent="#accordion" href="#POSITION-NAME">
	  	<div class="panel-heading">
	        <div class="panel-title">NAME OF POSITION, Department</div>
		</div>
	  </a>
	  
	  <div id="POSITION-NAME" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<h3>POSITION TITLE</h3>
	    	<h4>DEPARTMENT</h4>
	    	<h6 class="green">TIME/BENEFITS INFO</h6>
	    	<br />
	
			<h5>Salary</h5>
			<p></p>
			
			<h5>Hours</h5>
			<p></p>
			
			<h5>Job Summary</h5>
			<p></p>
			
			<h5>Responsibilities</h5>
			<p></p>
			
			<h5>Qualifications</h5>
			<p></p>
			
			<h5>Preferences</h5>
			<p>
				<ul>
					<li></li>
					<li></li>
					<li></li>
				 	<li></li>
				 	<li></li>
				 	<li></li>
				 	<li></li>
				 	<li></li>
				 	<li></li>
				 	<li></li>
				</ul>
			</p>
			
			<h5>To Apply</h5>
			<p><a href="#"></a></p>
			
		</div>
	  </div>
	  
	</div>


 End Job Template -->

</div>

</div>
</div>
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