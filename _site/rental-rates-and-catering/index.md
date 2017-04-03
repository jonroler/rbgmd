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
<title>Rental Rates & Catering</title>
    

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
		<div class="grid-header">PRIVATE AND CORPORATE EVENT RENTAL RATES</div>		
	<hr>
</div>

<br />

<p class="text-center">Escape from business as usual and retreat to the Garden. Just minutes from downtown Salt Lake City, the Richard K. Hemingway Orangerie offers incredible views of the Wasatch Mountains and the Salt Lake Valley. The Classroom, complete with audio-visual equipment, is a great space for smaller meetings, group training sessions, seminars and staff retreats. During warmer months, the Amphitheatre provides the perfect place for a company picnic or concert for your guests. This unique location offers a natural backdrop for your next meeting or event.</p>

<p class="text-center bold">Rental fee includes the use of the chosen facility, tables and chairs, on-site parking, and Garden admission for your guests during your event.</p>

<h3 class="text-center"><a href="/rental-availability">CLICK HERE FOR RENTAL SITE AVAILABILITY</a></h3>

<br />

<!-- Begin Orangerie Prices -->
<div class="tan-bg">

	<div class="row-fluid">
	
		<div class="col-sm-12">
			<h3 class="text-center green">ORANGERIE PRICES</h3>
		</div>
		
		<br />
		
		<div class="col-sm-12">
			
			<div class="row-fluid">
			
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/orangerie-event-05.jpg" alt="Red Butte Garden Orangerie" title="Red Butte Garden Orangerie" class="responsive" />
					<br />
					<br />
					<p class="text-center"><a href="/orangerie-event-photos">CLICK HERE for more Orangerie photos</a></p>
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					
					<h4 class="text-center">APRIL THROUGH DECEMBER</h4>
					
					<h5 class="green text-center">Monday through Thursday</h5>
					<h6 class="text-center">Morning (9am-2pm) $1300</h6>
					<h6 class="text-center">Evening (5pm-10pm) $2800</h6>
					
					<h5 class="green text-center">Friday or Sunday</h5>
					<h6 class="text-center">Morning (9am-2pm) $1800</h6>
					<h6 class="text-center">Evening (5pm-10pm) $3500</h6>
					
					<h5 class="green text-center">Saturday</h5>
					<h6 class="text-center">Morning (9am-2pm) $2500</h6>
					<h6 class="text-center">Evening (5pm-10pm) $3800</h6>
						
					<br />
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
				
					<h4 class="text-center">JANUARY THROUGH MARCH</h4>
					
					<h5 class="green text-center">Monday through Thursday</h5>
					<h6 class="text-center">Morning (9am-2pm) $1000</h6>
					<h6 class="text-center">Evening (5pm-10pm) $1500</h6>
					
					<h5 class="green text-center">Friday through Sunday</h5>
					<h6 class="text-center">Morning (9am-2pm) $1000</h6>
					<h6 class="text-center">Evening (5pm-10pm) $2000</h6>
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/orangerie-corporate.jpg" alt="Red Butte Garden Orangerie" title="Red Butte Garden Orangerie" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/orangerie-event-photos">CLICK HERE for more Orangerie photos</a></p>
				</div>
				
				<br class="br-hide-lg">
			
			
			</div>
	
		</div>
	
	</div>
	
	<br />

</div>
<!-- End Orangerie Prices -->

<br />

<!-- Begin Rose House and Rose Garden Prices -->
<div class="tan-bg">

	<div class="row-fluid">
	
		<div class="col-sm-12">
			<h3 class="text-center green">ROSE HOUSE & ROSE GARDEN PRICES</h3>
		</div>
		
		<br />
		
		<div class="col-sm-12">
			
			<div class="row-fluid">
			
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/rose-house-event.jpg" alt="Red Butte Garden Rose Garden" title="Red Butte Garden Rose Garden" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/rose-garden-event-photos">CLICK HERE for more Rose Garden photos</a></p>
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					
					<h4 class="text-center">MAY THROUGH OCTOBER</h4>
					
					<h5 class="green text-center">Monday through Thursday</h5>
					<h6 class="text-center">Morning (11am-3pm) $1300</h6>
					<h6 class="text-center">Evening (6pm-10pm) $2800</h6>
					
					<h5 class="green text-center">Friday or Sunday</h5>
					<h6 class="text-center">Morning (11am-3pm) $1800</h6>
					<h6 class="text-center">Evening (6pm-10pm) $3500</h6>
					
					<h5 class="green text-center">Saturday</h5>
					<h6 class="text-center">Morning (11am-3pm) $2500</h6>
					<h6 class="text-center">Evening (6pm-10pm) $3800</h6>
						
					<br />
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<p class="text-center"><strong>For inquiries about renting space in the Sponsor Terrace or Amphitheatre, reserving a time for an event, and any other event rental questions, please contact our Event Rentals Department at <span class="green">801-585-9563</span> or by email at <a href="mailto:rentals@redbutte.utah.edu">rentals@redbutte.utah.edu</a></strong></p>
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/rose-house-setup.jpg" alt="Red Butte Garden Rose House" title="Red Butte Garden Rose House" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/rose-house-event-photos">CLICK HERE for more Rose House photos</a></p>
				</div>
				
				<br class="br-hide-lg">
			
			
			</div>
	
		</div>
	
	</div>
	
	<br />

</div>
<!-- End Rose House and Rose Garden Prices -->

<br />

<!-- Begin Sponsor Terrace/Amphitheatre Prices -->
<div class="tan-bg">

	<div class="row-fluid">
	
		<div class="col-sm-12">
			<h3 class="text-center green">SPONSOR TERRACE/AMPHITHEATRE PRICES <span class="red">*</span></h3>
		</div>
		
		<br />
		
		<div class="col-sm-12">
			
			<div class="row-fluid">
			
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/amphitheatre-event-03.jpg" alt="Red Butte Garden Amphitheatre" title="Red Butte Garden Amphitheatre" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/amphitheatre-event-photos">CLICK HERE for more Amphitheatre photos</a></p>
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					
					<h4 class="text-center">MAY THROUGH SEPTEMBER</h4>
						
					<h5 class="green text-center">Monday - Thursday</h5>
					<h6 class="text-center">Morning (11am-3pm) $1300</h6>
					<h6 class="text-center">Evening (6pm-10pm) $2800</h6>
					
					<h5 class="green text-center">Friday or Sunday</h5>
					<h6 class="text-center">Morning (11am-3pm) $1800</h6>
					<h6 class="text-center">Evening (6pm-10pm) $3500</h6>
					
					<h5 class="green text-center">Saturday</h5>
					<h6 class="text-center">Morning (11am-3pm) $2500</h6>
					<h6 class="text-center">Evening (6pm-10pm) $3800</h6>
						
					<br />
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<p class="text-center"><strong><span class="red">* </span>For inquiries about renting space in the Sponsor Terrace or Amphitheatre, reserving a time for an event, and any other event rental questions, please contact our Event Rentals Department at <span class="green">801-585-9563</span> or by email at <a href="mailto:rentals@redbutte.utah.edu">rentals@redbutte.utah.edu</a></strong></p>
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/sponsor-terrace.jpg" alt="Red Butte Garden Sponsor Terrace" title="Red Butte Garden Sponsor Terrace" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/sponsor-terrace-event-photos">CLICK HERE for more Sponsor Terrace photos</a></p>
				</div>
				
				<br class="br-hide-lg">
			
			
			</div>
	
		</div>
	
	</div>
	
	<br />

</div>
<!-- End Sponsor Terrace/Amphitheatre Prices -->

<br />

<!-- Begin Classroom Prices -->
<div class="tan-bg">

	<div class="row-fluid">
	
		<div class="col-sm-12">
			<h3 class="text-center green">CLASSROOM PRICES <span class="red">*</span></h3>
		</div>
		
		<br />
		
		<div class="col-sm-12">
			
			<div class="row-fluid">
			
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/classroom-event-03.jpg" alt="Red Butte Garden Classroom" title="Red Butte Garden Classroom" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/classroom-event-photos">CLICK HERE for more Classroom photos</a></p>
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					
					<h5 class="green text-center">HALF-DAY RENTAL (up to 4 hours)</h5>
					<h6 class="text-center">$300</h6>
					<h5 class="green text-center">FULL-DAY RENTAL (up to 8 hours)</h5>
					<h6 class="text-center">$500</h6>
						
					<br />
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
				
					<p class="text-center"><strong><span class="red">* The Classroom cannot be reserved more than three months in advance.</span></p>
					<p class="text-center">For inquiries about renting space in the Classroom, reserving a time for an event, and any other event rental questions, please contact our Event Rentals Department at <span class="green">801-585-9563</span> or by email at <a href="mailto:rentals@redbutte.utah.edu">rentals@redbutte.utah.edu</a></strong></p>
				
				</div>
				
				<br class="br-hide-lg">
				
				<div class="col-sm-3">
					<br />
					<img src="/images/misc/classroom-event-02.jpg" alt="Red Butte Garden Classroom" title="Red Butte Garden Classroom" class="responsive" />
					<br /><br />
					<p class="text-center"><a href="/classroom-event-photos">CLICK HERE for more Classroom photos</a></p>
				</div>
				
				<br class="br-hide-lg">
			
			
			</div>
	
		</div>
	
	</div>
	
	<br />

</div>
<!-- End Classroom Prices -->

<br />

<h3 class="text-center"><a href="/rental-availability">CLICK HERE FOR RENTAL SITE AVAILABILITY</a></h3>

<br />

<h1 class="text-center green">OUR CATERERS</h1>

<br />

		
<!-- Begin Caterer Information -->
<div class="tan-bg">

	<br />
				
	<h4 class="bold text-center">All food and beverage services must be provided by one of the following caterers</h4>
	
	<p class="red text-center">Alcohol is permitted and must be served by your selected caterer</p>
	
	<div class="row-fluid">
	
		<div class="col-sm-4">
		
			<h4 class="green text-center">An Exquisite Affair</h5>
			<h6 class="text-center">(801) 278-7341</h6>
			<p class="text-center"><a href="http://exquisiteaffaircatering.com">exquisiteaffaircatering.com</a></p>
		
		</div>
		
		<div class="col-sm-4">
			
			<h4 class="green text-center">Cuisine Unlimited</h5>
			<h6 class="text-center">(801) 268-2332</h6>
			<p class="text-center"><a href="http://cuisineunlimited.com">cuisineunlimited.com</a></p>
			
		</div>
		
		<div class="col-sm-4">
			
			<h4 class="green text-center">Culinary Crafts</h5>
			<h6 class="text-center">(801) 355-6575</h6>
			<p class="text-center"><a href="http://culinarycrafts.com">culinarycrafts.com</a></p>
		
		</div>
		
	</div>
		
		<br />
		
	<div class="row-fluid">
		
		<div class="col-sm-4">
		
			<h4 class="green text-center">Good Day Catering</h5>
			<h6 class="text-center">(801) 532-7829</h6>
			<p class="text-center"><a href="http://gooddaycatering.com">gooddaycatering.com</a></p>
			
		</div>
		
		<div class="col-sm-4">
			
			<h4 class="green text-center">Have Party Will Travel</h5>
			<h6 class="text-center">(801) 269-8400</h6>
			<p class="text-center"><a href="http://havepartywilltravel.com">havepartywilltravel.com</a></p>
			
		</div>
		
		<div class="col-sm-4">
			
			<h4 class="green text-center">LeCroissant Catering</h5>
			<h6 class="text-center">(801) 466-2537</h6>
			<p class="text-center"><a href="http://lecroissantcatering.com">lecroissantcatering.com</a></p>
		
		</div>

	</div>
		
		<br />
		
	<div class="row-fluid">

		<div class="col-sm-4">
		
			<h4 class="green text-center">The Blended Table</h5>
			<h6 class="text-center">(801) 328-8138</h6>
			<p class="text-center"><a href="http://theblendedtable.com">theblendedtable.com</a></p>
			
		</div>
		
		<div class="col-sm-4">
			
			<h4 class="green text-center">Utah Food Services</h5>
			<h6 class="text-center">(801) 531-0226</h6>
			<p class="text-center"><a href="http://utahfoodservices.com">utahfoodservices.com</a></p>
			
		</div>
		
		<div class="col-sm-4">
			
			<h5 class="text-center">For further information on renting the Garden:</h5>
			<h6 class="text-center">(801) 585-9563</h6>
			<p class="text-center"><span class="green">EMAIL:</span> <a href="mailto:rentals@redbutte.utah.edu">rentals@redbutte.utah.edu</a></p>
		
		</div>
		
	</div>
				
	<br />

</div>
			

<br />

<p class="red text-center"><em>* All pricing is subject to change</em></p>

<p class="red text-center"><em>*** All of the information above is provided 'as is' and is subject to change. For inquiries about renting space in the Garden, reserving a time for an event, and any other event rental questions, please contact our Event Rentals Department at 801-585-9563 or by email at <a href="mailto:rentals@redbutte.utah.edu">rentals@redbutte.utah.edu</a>***</em></p>

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