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
<title>School Field Classes</title>
    

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
		<div class="grid-header">SCHOOL FIELD CLASSES</div>		
	<hr>
</div>

<br />

<!-- Begin Field Class Info -->	
<div class="row-fluid">

	<div class="col-md-4 lowpadding">
		
			<div class="meminfo memcorp field-class-info">
			
				<h4 class="text-center green">GUIDED FIELD CLASSES:</h4>
				<p class="text-center">Two-hour guided field classes are designed to meet the standards and objectives of the Utah State Core Curriculum at each grade level, focusing on hands-on activities that will engage and delight students of all ages. All classes are held rain or shine, and are led by either a Red Butte Garden Education Staff member or a trained Education Volunteer.</p>
				
				<p class="text-center green bold">Fall guided field classes are offered September 1 through October 15, 2016, Mondays-Thursdays</p>
				
				<p class="text-center green bold">Spring guided field classes are offered April 3 through June 2, 2017, Mondays-Thursdays</p>
				
				<p class="text-center red">All Spring 2017 Field Classes are currently full</p>
				<!--This is a swag.-->
				
			</div>

	</div>
	
	<div class="col-md-4 lowpadding">
		
		<div class="meminfo memcorp field-class-info">
			
			<h4 class="text-center green">RED BUTTE GARDEN AND NATURAL HISTORY MUSEUM EXPERIENCE:</h4>
			<br />
			<img src="/images/misc/rbg-nhmu-experience.jpg" alt="Red Butte Garden / Natural History Museum of Utah Experience" title="Red Butte Garden / Natural History Museum of Utah Experience" class="responsive" />
			<br /><br />
			<p class="text-center"><a href="/rbg-nhmu-experience">CLICK HERE to book a same-day field trip experience with Red Butte Garden and the Natural History Museum of Utah</a></p>
			<!--This is a swag.-->
				
		</div>
		
	</div>
	
	<div class="col-md-4 lowpadding">

			<div class="meminfo memcorp field-class-info">
			
				<h4 class="text-center green">SELF-GUIDED FIELD CLASSES:</h4>
				<p class="text-center bold">Self-guided field classes are offered on Fridays during the school year</p>
				<center><img src="/images/misc/field-classes-03.jpg" alt="Red Butte Garden Field Classes" title="Red Butte Garden Field Classes" class="responsive" style="max-width:250px;" /></center>
				<br />
				<p class="text-center"><a href="https://redbuttegarden.formstack.com/forms/field_class_request">CLICK HERE to request a Guided or Self-Guided Field Class</a></p>
				<!--This is a swag.-->
				
			</div>
		
	</div>		
			
</div>
<!-- End Field Class Info -->

<h3 class="text-center"><a href="https://redbuttegarden.formstack.com/forms/field_class_request">CLICK HERE to request a Guided or Self-Guided Field Class</a></h3>

<br />

<!-- Begin Admission Info -->


<div class="memfaqwrap hover">
	<div class="volbutton green-bg" data-target="#admission-info" data-toggle="collapse">ADMISSION INFORMATION</div>
</div>

<div class="collapse panel-border tan-bg" id="admission-info">

	<br />
	
	<div class="row-fluid tan-bg">

		<div class="col-sm-12">

			<p class="text-center red">Reservations are required for all field trips</p>
			<p class="text-center">We require one adult chaperone for every 7 students. Students, teachers, and chaperones in <strong>Public and Charter schools</strong> within the 1:7 adult to student ratio are admitted free of charge. Chaperones exceeding the 1:7 adult to student ratio are admitted at a reduced entrance fee of $11.00 per person.</p>
			<p class="text-center"><strong>Private school and home school students</strong> are admitted at a group rate of $5.00 per student. Adults and chaperones within the required 1:7 adult to student ratio are admitted free of charge. Chaperones exceeding the 1:7 ratio are admitted at a reduced entrance fee of $11.00 per person.</p>
			<p class="text-center">Note that GUIDED GARDEN TOURS can be arranged for non-school groups. <a href="/garden-tours">MORE INFO</a></p>
		
		</div>

	</div>
	
	<br />
	
</div>

<!-- End Admission Info -->

<br />

<!-- Begin Field Class Offerings -->

<div class="memfaqwrap hover">
	<div class="volbutton" data-target="#field-classes" data-toggle="collapse">FIELD CLASS OFFERINGS</div>
</div>

<div class="collapse panel-border tan-bg" id="field-classes">

	<br />

	<!-- Begin Grade-by-Grade Descriptions -->
	
	<div class="row-fluid">
		
		<div class="col-sm-4">
			<h4 class="text-center green">Kindergarten</h4>
			<p class="text-center">Students explore the Garden using their five senses. This 90-minute lesson will excite our youngest adventurers.</p>
		</div>
		
		<div class="col-sm-4">
			<h4 class="text-center green">1st Grade</h4>
			<p class="text-center">Students explore plant parts with hands-on activities at discovery stations throughout the Garden. Activities include: dissecting a lima bean, dissecting a flower, and observing all plant parts in a variety of settings.</p>
		</div>
		
		<div class="col-sm-4">
			<h4 class="text-center green">2nd Grade</h4>
			<p class="text-center">Students learn about the life cycle of plants, including pollination, seed dispersal, and plant development with hands-on activities throughout the Garden.</p>
		</div>
		
	</div>
	
	<br />
	
	<div class="row-fluid">
		
		<div class="col-sm-4">
			<h4 class="text-center green">3rd Grade</h4>
			<p class="text-center">Put on your hiking shoes! Students learn about the adaptations of native plants and animals, as well as interrelationships that occur in the Natural Area of the Garden. This two-mile hike/tour in the foothills of Salt Lake City includes searching for animal signs and learning about habitats and ecosystems.</p>
		</div>
		
		<div class="col-sm-4">
			<h4 class="text-center green">4th Grade</h4>
			<p class="text-center">Student naturalists will hone in on concepts introduced in third grade, such as ecosystems, habitats, and interrelationships. Additionally, students will explore and identify native plants and animals while hiking through Red Butte Garden's Natural Area.</p>
		</div>
		
		<div class="col-sm-4">
			<h4 class="text-center green">5th and 6th Grade</h4>
			<p class="text-center">On a self-guided tour, students can explore Red Butte Garden under the supervision of their teachers and chaperoning adults.</p>
		</div>
		
	</div>

	<br />

	<div class="row-fluid">
		
		<div class="col-sm-4">
			<h4 class="text-center green">Secondary School Programs</h4>
			<p class="text-center">Self-guided tours allow teachers to bring their students up to discover the beauty and wonder of the Garden.</p>	
		</div>
		
		<div class="col-sm-4">
			<h4 class="text-center green">In Your Classroom (Title One Schools)</h4>
			<p class="text-center">Red Butte Garden offers Title One schools a Garden staff member to teach both the pre-visit and post-visit activity in the classroom. When you schedule your field trip to the Garden, please mention that you are a Title One school.</p>
			<p class="text-center">Teachers have told us that this program has dramatically increased the level of understanding during the field experience at the Garden and in meeting core curriculum requirements. To get this program started in your classroom or to give us feedback, please contact the Red Butte Garden education department.</p>
			<p class="text-center bold">Title One Field Class Program, School Programs, 300 Wakara Way, Salt Lake City, UT 84108</p>
	
		</div>	
		
		<div class="col-sm-4">
			<h4 class="text-center green">Self-Guided Exploration</h4>
			<p class="text-center">Using maps of the Garden, students and teachers can chart their own exploratory adventure through Red Butte Garden. Fridays only during school programs months (see above).</p>	
		</div>	
		
	</div>
	
	<!-- End Grade-by-Grade Descriptions -->

	<br />

</div>
<!-- End Field Class Offerings -->

<br />

<!-- Begin Field Class Calendar Panel -->
	
<div class="memfaqwrap hover">
	<div class="volbutton green-bg" data-target="#field-class-calendar" data-toggle="collapse">FIELD CLASSES CALENDAR</div>
</div>

<div class="collapse panel-border" id="field-class-calendar">
	
	<br />
	
	<iframe src="https://calendar.google.com/calendar/embed?title=RBG%20-%20School%20Field%20Classes&amp;height=400&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=gcloud.utah.edu_olcsoo5se09ocau8q49gutmnog%40group.calendar.google.com&amp;color=%23711616&amp;ctz=America%2FDenver" style="border-width:0" width="100%" max-width="1280px" height="400px" frameborder="0" scrolling="no"></iframe>

	<br />
	
</div>
		
<!-- End Field Class Calendar Panel -->

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