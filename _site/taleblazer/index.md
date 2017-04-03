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
<title>TaleBlazer Mobile Games</title>
    

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
		<div class="grid-header">TaleBlazer Mobile Games</div>		
	<hr>
</div>
<br />

<h3 class="text-center green">Visit the Garden to Play!</h3>

<div class="row-fluid">

	<div class="col-sm-3">
		<img src="/images/events/taleblazer.jpg" alt="Play TaleBlazer at Red Butte Garden" title="Play TaleBlazer at Red Butte Garden" class="responsive" />
	</div>
	
	<div class="col-sm-9">
		<p>Interact with the Garden in a new and exciting way! Using GPS-enabled smart phones and the Massachusetts Institute of Technology’s TaleBlazer software, the Garden has created five free-choice games that require users to gather input from Garden surroundings and demonstrate their understanding to progress through the games. Whether you’re identifying plants to use at your 5-star restaurant or applying navigation skills to find buried treasure, get ready for a virtual adventure!</p>
		
		<p>Red Butte Garden’s TaleBlazer games are free of charge and available for download on any GPS-enabled tablet or smart phone. You will need either a Wi-Fi connection or a data plan to install TaleBlazer and initially download games, but no connection or data is used while playing.</p>
		
		<p>Check out this article about the new games.<br />
		<a href="http://www.sltrib.com/blogs/cricket/2240294-155/red-butte-garden-launches-interactive-games">http://www.sltrib.com/blogs/cricket/2240294-155/red-butte-garden-launches-interactive-games</a></p>
		
		<h6 class="green">How to download:</h6>
		
		<ul>
			<li>Search for “TaleBlazer” in either the Google Play Store (Android devices) or App Store (Apple devices) and download the free TaleBlazer app.</li>
			<li>Load the app and press “Play” under Red Butte Garden on the Home screen to browse and download available games.</li>
		</ul>
	
	</div>
	
</div>

<br />
<hr>
<br />

<div class="row-fluid">
	
	<h3 class="text-center green">Available Games</h3>
	<br />
	
	<div class="col-sm-2">
		<img src="/images/misc/garden-tales.jpg" alt="Garden Tales" title="Garden Tales" class="responsive" />
	</div>
	
	<div class="col-sm-10">
	<h4 class="green">Garden Tales</h4>
	<p>
		<strong>Location:</strong>Courtyard Garden & Four Seasons Garden<br />
		<strong>Duration:</strong> 15-25 minutes<br />
		<strong>Best Time to Play:</strong> Year round<br />
		<strong>Difficulty:</strong> Beginner
	</p>
	
	<p>Interact with Chauncey, Red Butte Garden’s resident gnome, to learn Garden etiquette and practice TaleBlazer basics in this tutorial game.</p>
	
	<p>
		<strong>Learn More</strong><br />
		<a href="www.taleblazer.org">www.taleblazer.org</a>
	</p>
	</div>
	
</div>

<br />
<hr>
<br />

<div class="row-fluid">

	<div class="col-sm-2">
		<img src="/images/misc/lady-nightshade.jpg" alt="Lady Nightshade" title="Lady Nightshade" class="responsive" />
	</div>
	
	<div class="col-sm-10">
	<h4 class="green">Lady Nightshade and the Invaders</h4>
	
	<p>
		<strong>Location:</strong> Water Pavilion Garden<br />
		<strong>Duration:</strong> 25-35 minutes<br />
		<strong>Best Time to Play:</strong> March-October<br />
		<strong>Difficulty:</strong> Intermediate<br />
	</p>
	
	<p>Assemble an army to defeat the evil Lady Nightshade and her invading warriors! Learn about native plants and invasive species issues while exploring the Garden’s Water Pavilion in this fantasy adventure game.</p>
	
	<p>
		<strong>Learn More</strong><br />
		<a href="http://slco.org/weeds/">Salt Lake County Weed Control</a><br />
		<a href="http://www.eddmaps.org/west/about/">EDDMapS</a><br />
		<a href="https://www.facebook.com/UtahNoxiousPlants">Urban Habitat</a><br />
	</p>
	</div>
	
</div>

<br />
<hr>
<br />

<div class="row-fluid">	
	
	<div class="col-sm-2">
		<img src="/images/misc/water-games.jpg" alt="Water Games" title="Water Games" class="responsive" />
	</div>
	
	<div class="col-sm-10">
	<h4 class="green">Water Games</h4>
	<p>
		<strong>Location:</strong> Children’s Garden<br />
		<strong>Duration:</strong> 10-35 minutes<br />
		<strong>Best Time to Play:</strong> March-September<br />
		<strong>Difficulty:</strong> Intermediate
	</p>
	
	<p>Can you make water-efficient choices? Learn about water conservation while increasing the water supply to your home village of Trickleton as you explore the Children's Garden.</p>
	
	<p>
		<strong>Learn More</strong><br />
		<a href="http://conservewater.utah.gov/tips.html">Utah Division of Water Resources</a><br />
		<a href="http://www.slowtheflow.org/">Slow the Flow</a><br />
		<a href="http://wateruseitwisely.com/">Water-Use It Wisely</a><br />
		<a href="http://extension.usu.edu/utahwaterwatch/">Utah Water Watch</a><br />
		<a href="http://www.desertmuseum.org/programs/succulents_adaptation.php">Desert Plant Adaptations</a><br />
		<a href="http://www.desertmuseum.org/books/nhsd_adaptations_birds.php">Desert Animal Adaptations</a>
	</p>
	
	</div>
	
</div>

<br />
<hr>
<br />

<div class="row-fluid">
	
	<div class="col-sm-2">
		<img src="/images/misc/garden-fresh.jpg" alt="Garden Fresh" title="Garden Fresh" class="responsive" />
	</div>
	
	<div class="col-sm-10">	
	<h4 class="green">Garden Fresh!</h4>
	<p>
		<strong>Location:</strong> Courtyard Garden, Herb Garden, & Medicinal Garden<br />
		<strong>Duration:</strong> 25-35 minutes<br />
		<strong>Best Time to Play:</strong> May-August<br />
		<strong>Difficulty:</strong> Intermediate
	</p>
	
	<p>Help your restaurant earn a 5-star rating by selecting the correct garden fresh ingredients. Play the role of an assistant chef and help fill customers’ orders by correctly identifying plants in the Garden.</p>
	
	<p>
		<strong>Learn More</strong><br />
		<a href="http://www.ediblewasatch.com/resources/farmers-markets">Utah Farmers Markets</a><br />
		<a href="https://wasatchgardens.org/community">Finding a Community Garden</a><br />
		<a href="http://www.pfaf.org/user/edibleuses.aspx">Plant Uses</a><br />
		<a href="http://umm.edu/health/medical/altmed">Medicinal Uses of Plants</a><br />
		<a href="http://www.getlocavore.com/">Locavore App</a>
	</p>
	</div>
	
</div>

<br />
<hr>
<br />

<div class="row-fluid">	

	<div class="col-sm-2">
		<img src="/images/misc/captain-bonneville.jpg" alt="Captain Bonneville" title="Captain Bonneville" class="responsive" />
	</div>
	
	<div class="col-sm-10">
	<h4 class="green">Captain Bonneville</h4>
	<p>
		<strong>Location:</strong> Natural Area<br />
		<strong>Duration:</strong> 45-55 minutes<br />
		<strong>Best Time to Play:</strong> Year round<br />
		<strong>Difficulty:</strong> Advanced (longer game, includes significant hike)
	</p>
	
	<p>Can you find Captain Bonneville's missing treasure? Test your navigation skills and geographic knowledge while exploring Red Butte Garden's natural area.</p>
	
	<p>
	<strong>Learn More</strong><br />
		<a href="http://geology.utah.gov/popular-geology/general-geology/great-salt-lake/#tab-id-2">Lake Bonneville</a><br />
		<a href="http://geology.utah.gov/popular-geology/general-geology/dinosaurs-fossils/age-of-dinosaurs/">Utah in the Age of Dinosaurs</a>
	</p>
	
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