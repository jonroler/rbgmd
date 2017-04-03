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
<title>How To Buy Tickets</title>
    
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
		<div class="grid-header">HOW TO BUY CONCERT TICKETS</div>
	<hr>
</div>

<div class="row-fluid">

	<div class="col-xs-12">

	<br />

		<h3 class="text-center"> 2017 Outdoor Concert Series</h3>
		<h4 class="green text-center"> To purchase, renew, or upgrade your Garden Membership please call 801-585-7172 or visit our <a href="/memberships">Membership page.</a> </h4>

		<p class="text-center">Red Butte Garden uses an external ticketing system called Ticketfly. You must set up a Ticketfly account BEFORE you can purchase concert tickets online. </p>

<div class="row-fluid">

	<div class="col-sm-3">

		<h4 class="green text-center">Ticket Information</h4> 
		<h5 class="text-center">GARDEN MEMBER TICKET PRESALES:</h5>
		<h6 class="text-center">Monday, April 24 at 7PM - Online-Only</h6>
		<h6 class="text-center">Tuesday, April 25 at 9AM - In-person &amp; Online</h6>
		 
		<p class="text-center"><strong>Membership Deadline – Friday, April 21</strong><br />
		Renew or purchase a Garden-Plus Membership level or above by April 21 in order to participate in the April 24 Member-Only Online presale.</p>

		<ul>
			<li>Membership sales will not be available April 22 through April 24</li>
			<li>Membership sales will resume on Tuesday, April 25</li>
		</ul>

		<p class="text-center red">Please note: Garden Membership does not guarantee concert ticket availability.</p>
		 
		<h5 class="text-center">GENERAL PUBLIC TICKET SALES:</h5>
		<h6 class="text-center">Monday, May 1 at 9AM - In-Person &amp; Online sales</h6>

	</div>

	<div class="col-sm-3">

		<h4 class="green text-center"> Ticketfly Registration Process </h4>

		<ul>
			<li>You must establish a Ticketfly account in order to purchase concert tickets online</li>
			<li>To set up an account go to: <a href="http://ticketfly.com">www.ticketfly.com</a></li>
			<li>Click on "My Account" </li>
			<li>Click on "Register", follow the instructions and establish a Ticketfly password</li>
		</ul>

	</div>

	<div class="col-sm-3">

		<h4 class="green text-center"> How To Buy Tickets Online </h4>

		<ul>
			<li><strong>FYI:</strong> Because only a limited amount of tickets are available to any show, some concerts may sell-out quickly – sometimes in less than 10 minutes.</li>
			<li><strong>Important!</strong> Garden Members &amp; General Public: SET UP and LOG IN to your Ticketfly account with your Ticketfly account password BEFORE tickets go on sale</li>
			<li><strong>Garden Members:</strong> After logging in to Ticketfly, use the email address associated with your Garden Membership as your "Promo Code,” this allows you to participate in the Member-only presale AND get your Member discount on concert tickets</li>
			<li><strong>Still need help?</strong> Check out the How-To-Buy video below</li>
			<li>If you are unsure of your Garden Member Promo Code, please email <a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a> PRIOR to the presale date</li>
		</ul>

	</div>

<div class="col-sm-3">

	<h4 class="green text-center"> Where To Purchase </h4>
	<h5> There is a $5 Order-Processing fee per order for ALL ticket orders: online, phone, or in-person. </h5>
		<h6> 1. Online </h6>
		<ul>
			<li> Go to: <a href="http://redbuttegarden.ticketfly.com">www.redbuttegarden.ticketfly.com</a></li>
			<li> $4.50 per ticket Ticket Fee for online purchases </li>
		</ul>
		<h6> 2. Phone</h6>
		<ul>
			<li> Ticketfly: 877-987-6487 (Mon-Sat 7AM-6PM PST, Sun 10AM-6PM PST). $4.50 per ticket Ticket Fee plus $1.50 per ticket Phone Order fee for Ticketfly phone orders </li>
		</ul>
		<h6> 3. In-Person </h6>
		<ul>
			<li> Red Butte Garden Visitor Center open daily at 9AM </li>
			<li> 300 Wakara Way, Salt Lake City, UT 84108 </li>
			<li> No per ticket Ticket Fee - Leave with tickets in hand </li>
		</ul>

</div>

</div>

		<p class="text-center"><b>Still need help? Check out the How To Purchase video instructions. </b></p>
		<p class="text-center"><iframe width="560px" height="315px" src="https://www.youtube.com/embed/SaLaPUQeskw" frameborder="0" allowfullscreen></iframe></p>

			<h4 class="green text-center"> All sales are final. No refunds, replacements or exchanges. All shows rain or shine. For more information visit our CONCERT FAQ page. </h4>
			<h5 class="text-center"> Be aware that other ticket vendors and scalpers use the words 'Red Butte' in some way to sell tickets. We recommend that you only purchase your tickets online through www.redbuttegarden.org or www.ticketfly.com. </h5>
			<h3 class="text-center"> CONCERT TICKET TERMS & CONDITIONS </h3>
			<h5> A ticket to a Red Butte Garden concert is a license from Red Butte Garden to attend the concert event. Purchasers agree to, and must comply with, certain terms and conditions. These terms and conditions include:</h5>
			<ul>
				<li> A prohibition on ticket scalping; aka overcharging </li>
				<li> A prohibition on improper or disruptive behavior at concert events </li>
				<li> Limitations on the number of tickets that may be purchased </li>
				<li> Prohibitions on certain purchasing methods and practices </li>
				<li> Rules regarding refunds and exchanges </li>
				<li> Prohibitions on recording and transmitting of concert events</li>
			</ul>
			<h5> See a complete list and more details regarding these Terms & Conditions HERE. Failure to abide by the terms and conditions may result in exclusion from Red Butte Garden concerts and events, forfeiture of tickets, and banning of further purchase of Red Butte Garden concert and event tickets. </h5>
			<h4 class="green text-center"> Children</h4>
				<p class="text-center"> Children age 3 and younger do not need tickets. </p>

			<h4 class="green text-center"> How To Pick Up Tickets </h4>
				<p class="text-center"> Ticketfly offers multiple ticket delivery options, including print-at-home, mail, and Will Call. </p>
				<h5> *Photo ID required at Red Butte Garden Visitor Center Box Office and Amphitheatre Will Call Booth. Tickets may only be picked up by the purchaser. </h5>
			<h4 class="green text-center"> Day-Of-Show Tickets </h4>
				<ul>
					<li> Ticket prices increase on the day of the show </li>
					<li> There are no Garden Member discounts on day-of-show tickets </li>
				</ul>
			<h4 class="green text-center"> Red Butte Garden Member Benefits For Concerts </h4>
				<h5> Become a Garden Member and receive the following concert benefits:</h5>
					<ul>
						<li> Participate in the member-only Outdoor Concert Series ticket pre-sale </li>
						<li> Receive a discount: Concert tickets are $5.00 less per ticket for Garden Members than for the General Public </li>
						<li> See more membership benefits HERE </li>
					</ul>
				<h5> Members may purchase the following # of tickets at the discounted rate: </h5>
					<ul>
						<li>Garden-Basic membership level - 0 </li>
						<li>Garden-Plus membership level - 2 </li>
						<li>Family, Family-Plus, &amp; Circle of Friends membership levels - 4 </li>
						<li>Contributor &amp; Forget-Me-Not membership levels - 6 </li>
						<li>Blazing Star, Avant Gardener &amp; Director's Club membership levels - 8 </li>
					</ul>

				<h4 class="green text-center"> To become a Garden Member, call the Membership Department at 801-585-7172 or visit our <a href="/memberships">Membership page.</a> Renew or upgrade your Garden Membership before concert tickets go on sale! </h4>

				<h5 class="text-center red"> Please Note: Garden Membership does not guarantee concert tickets. </h5>

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