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
<title>Concert FAQs</title>
    
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


<!-- DO NOT TOUCH! (adds code for Concert Sponsor Banner to be on page) -->
	<div id="concert-sponsors-banner">
	<img src="/images/concert-images/sponsors/concert-sponsors-2016.jpg" alt="Concert Sponsors" title="Concert Sponsors" />
</div>
<!-- DO NOT TOUCH! -->

<div id="rbgdefaultbody" class="container-fluid">
  <div class="row">
  	  <div class="col-sm-12">
        <div class="eventdivide">
	<hr>
		<div class="grid-header">CONCERT INFORMATION - FAQ</div>		
	<hr>
</div>

<div class="row-fluid">

	<div class="col-xs-12">
		<h4>For information on how to purchase and pick up tickets,<br/>
		visit our <a href="/events/how-to-buy-tickets">HOW TO BUY TICKETS</a> page.</h4>
		
		<br />
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>TICKET SCALPING</b></h3>
		
		<p>Be aware that other ticket vendors and scalpers use the words 'Red Butte' in some way to sell tickets. We recommend that you only purchase your tickets online through <a href="http://www.redbuttegarden.org" title="www.redbuttegarden.org">www.redbuttegarden.org</a> or <a href="http://www.ticketfly.com" title="www.ticketfly.com">www.ticketfly.com</a>.</p>
		
		<p>Purchasers of Red Butte Garden concert and event tickets may not resell their tickets for more than the face value of the ticket ("scalping"). Purchasers who are caught scalping their tickets may be subject to ejection from the Red Butte Garden event, may have their tickets confiscated, and may be banned from the future purchase of tickets to Red Butte Garden events. <a href="/concert-terms-conditions">CLICK HERE</a> to see all of the Terms &amp; Conditions that apply to your concert ticket ("license"). </p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>CONCERT LINE GUIDELINES</b></h3>
		
		<p>The Red Butte Garden Amphitheatre is a first come, first serve general admission venue.</p>
		
		<ul>
			<li>Waiting in line overnight is not permitted. </li>
			<li>Concert-goers must remain with their spot in line throughout the day. A reasonable 20 minute break to the car or restroom is acceptable. It is not allowed to leave blankets or chairs and then take off for an extended period of time. Red Butte Garden staff will remove your items from the line.</li>
			<li>No one is allowed to join parties already in line after 5PM, additional party members can join at the end of the line and connect with you inside.</li>
			<li>Please be friendly and respectful to others in line.</li>
		</ul>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>NO RE-ENTRY</b></h3>
		
		<p>Once you have entered the Amphitheatre, you may not exit and re-enter. You are welcome to bring food, blankets, low-rise chairs, etc. into the venue with you. Be prepared for weather extremes such as sunshine, heat, wind, or rain. Bring a jacket, as the temperature may drop noticeably after sunset.</p>
		
		<hr noshade size=3 />
		
		<div class="row-fluid">
		
			<div class="col-sm-8">
				
				<h3 class="green"><b>CHAIR &amp; BLANKET RULES</b></h3>
				
				<p>You are welcome to bring your own <b>low-back chair</b> or blanket.<br/>
				• 12” max from ground to front of seat bottom<br/>
				• 30” max to top of chair back in highest position</p>
				
				<p>Red Butte Garden reserves the right to limit the number and size of blankets used by individuals or groups.</p>
				
			</div>
			
			<div class="col-sm-4">
				<img src="../../images/concert-images/concert-chair-dimensions.jpg" alt="Concert Chair Dimensions" title="Concert Chair Dimensions" class="responsive" />
			</div>
			
		</div>
		
		<p><br/></p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>PHOTOGRAPHY</b></h3>
		
		<p>Recording and transmission at concerts is generally prohibited. Cameras with removable lenses, video cameras, and recording devices are prohibited.<br/>
		No flash photography. At some shows photography will not be allowed at all. </p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>FOOD &amp; BEVERAGE</b></h3>
		
		<p> • Food and non-alcoholic beverages will be available for sale.<br/>
		• You are welcome to bring a cooler and pack your own picnic.<br/>
		• No cooking or barbecues allowed.<br/>
		• Please pack out whatever you bring into the venue. </p>
		
		<p><b>CUISINE UNLIMITED</b> is the Red Butte Garden Outdoor Concert Series food vendor this summer. Save time and preorder your concert picnic online and pick it up at the Cuisine Unlimited Concert Café located inside the Amphitheatre. </p>
		
		<p><b>Click Here: <a href="http://www.cuisineunlimited.com/redbutte/"> Concert Café Preorder Menu </a></b></p>
		
		<p><img src="../../images/concert-images/cuisine-unlimited-menu.jpg" alt="Cuisine Unlimited Menu" title="Cuisine Unlimited Menu" class="responsive" /></p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>WEATHER</b></h3>
		
		<p>All concerts are held rain or shine. Be prepared for extremes such as sunshine, heat, wind, or rain. Dress accordingly, as the temperature may drop noticeably after sunset. </p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>DISRUPTIVE &amp; IMPROPER CONDUCT</b></h3>
		
		<p>Participants are expected to conduct themselves in an orderly fashion and to refrain from conduct and language that would be offensive and/or disruptive to performers or other event participants. Participants who violate these rules may be ejected from the event. <a href="/concert-terms-conditions">CLICK HERE</a> to see all of the Terms &amp; Conditions that apply to your concert ticket ("license"). </p>
		<hr noshade size=3 />
		
		<h3 class="green"><b>SMOKING &amp; VAPING</b></h3>
		
		<p>In compliance with the Utah Clean Air Act and to protect our plant collections and concertgoers, Red Butte Garden is a non-smoking facility. Smoking and vaping are permitted only in the designated area outside the main entrance gate. Thank you for your cooperation. </p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>MOBILITY IMPAIRMENTS</b></h3>
		
		<p>Red Butte Garden implements the following policy for the Outdoor Concert Series:</p>
		
		<ul>
			<li>We provide a designated area west of the Sponsor entrance gate where concertgoers with <i>mobility impairment disabilities</i>, minor children and one guest may gather
			</li><li>Other members of your group may meet you inside the Amphitheatre after they enter through the sponsor gate or general admission gate</li>
			<li>There is no early entry </li>
			<li>The wheelchair accessible designated seating area is located on the west side of the soundboard where there are wheelchair symbols on the path</li>
		</ul>
		
		<p>
		If you have any questions or concerns regarding this policy, please contact the Red Butte Garden Visitor Center at 801-585-0556.
		</p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>PETS</b></h3>
		
		<p>Only Service Animals are allowed in the Garden or Amphitheatre. Leave pets and comfort animals at home. </p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>DAY OF SHOW TICKETS</b></h3>
		
		<p>Ticket prices increase on the day of the show. There are no Garden Member discounts on day-of-show tickets.</p>
		
		<hr noshade size=3 />
		
		<h3 class="green"><b>PARKING</b></h3>
		
		<p>The Amphitheatre is part of Red Butte Garden, but it is located at a different address than the RBG Visitor Center. </p>
		
		<p>Red Butte Garden Amphitheatre<br/>
		2155 Red Butte Canyon Rd.<br/>
		Salt Lake City, UT 84108</p>
		
		<p>Parking is free, but limited, adjacent to the Amphitheatre (see map). We encourage you to bike, car pool, or take public transportation. Free bike valet is provided by the <a href="http://www.bicyclecollective.org/">Salt Lake City Bicycle Collective.</a> To plan your route to the Amphitheatre using public transit, visit: <a href="http://www.rideuta.com">www.rideuta.com.</a> </p>
		
		<p><img src="../../images/concert-images/concert-parking-map.jpg" alt="Concert Parking Map" title="Concert Parking Map" class="responsive" /><br/>
		
		Click <a href="http://www.redbuttegarden.org/sites/default/files/ParkingMap__Print.pdf" title="">HERE</a> for a larger, printable map.</p>
	
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