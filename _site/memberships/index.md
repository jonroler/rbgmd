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
<title>Garden Membership | Red Butte Garden</title>
    

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
        <div class="row-fluid">
	<img src="/images/banners/memberships.jpg" class="responsive" alt="Memberships at Red Butte Garden" title="Memberships at Red Butte Garden" />
</div>

<br />

<div id="memcontain">

<p>Membership at Red Butte Garden gives you the opportunity to experience every season uniquely, connect with nature in a rewarding way, and maybe attend a few concerts featuring world-renowned musicians in the beautiful Red Butte Garden Amphitheatre. </p>

<p>Membership benefits include Garden admission for 12 months and free admission at many events and programs such as Monday Family Nights, Orchid and Bonsai Exhibits, Art Exhibits, and guided Garden tours.</p>

<p>Need the perfect gift for your favorite garden enthusiast? Share the beauty of the Garden through a Gift Membership at any level. Find your perfect fit below.</p>

<p><span style="color:#FF0000;font-style:italic;">Please note: Garden Memberships are not refundable or transferable, and Membership does not guarantee concert tickets. For a complete list of membership policies, please refer to the Garden Policies section below:</span></p>

<div class="row">

<!-- Begin Garden Membership Benefits -->
	<div class="col-sm-6 lowpadding">
	
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#membenefits" data-toggle="collapse">Garden Membership Benefits</button>
		</span>
		
		<div class="collapse" id="membenefits">
			<br />
			
			<h3>Benefits of Garden Membership</h3>
	
			<h4>A Year of Free Events and Programs</h4>
			
			<ul>
				<li>Garden Admission for 12 months and all four distinctive seasons*</li>
				<li><a href="#">Guided Complimentary &amp; Specialty Tours </a> of the Garden</li>
				<li><a href="#">Monday Family Nights</a></li>
				<li><a href="#">Orchid &amp; Bonsai Shows</a></li>
				<li><a href="#">Art Exhibits</a></li>
				<li><a href="#">Member-Only Day at the Annual Spring Plant Sale</a></li>
				<li><a href="#">Quarterly Newsletter</a> and a monthly e-mail update of Garden events</li>
			</ul>
			
			<p><i>*Unlimited Garden Admission does not include concerts or separately ticketed events.</i></p>
			
			<br />
			
			<h4>A Year of Great Discounts</h4>
			
			<ul>
				<li><a href="#">Up to 20% off adult education</a> at Red Butte Garden</li>
					<ul>
						<li>Seasonal Workshops</li>
						<li>Horticulture and gardening classes</li>
						<li>University of Utah Continuing Education Lifelong Learning classes</li>
					</ul>
				<li>Up to 20% off family-friendly programming</li>
					<ul>
						<li><a href="#">Summer Camps</a></li>
						<li><a href="#">Garden Adventures</a></li>
						<li><a href="#">Day Camps</a></li>
					</ul>
				<li>50% discount on <a href="#">Garden After Dark tickets</a></li>
				<li>50% off guest coupons for a day in the Garden</li>
				<li>10% off at the <a href="#">Gift Shop</a> at Red Butte Garden</li>
				<li>10-20% Discount with <a href="#">Local Retail Partners</a></li>
				<li>The American Horticulture Society's <a href="http://www.ahsgardening.org/rapgardens" target="_blank">Reciprocal Admissions Program</a> offers free admission and/or additional benefits at 300 gardens throughout North America and the Cayman Islands.</li>
				<li><a href="/concerts">Red Butte Garden Outdoor Concert Series</a> exclusive early access and discounts for <span class="lilac">Garden-Plus</span> level and above</li>
			</ul>
			
			<center>
			<h4>Questions?</h4>
			
			<p><b>See the <a href="/membership-FAQ">Membership FAQs</a></b> </p>
			
			<p><i>Member Benefits are subject to change.<br/>
			Please note that Garden Memberships are not refundable or transferable.<br/></i></p>
	
			<p><a href="https://55218.blackbaudhosting.com/55218/Garden-Membership"><input type="submit" name="Membership-button" value="Buy or Renew Garden Membership" class="renewbutton" /></a></p>
			</center>		
			<br />
		
		</div>
			
	</div>
<!-- End Garden Membership Benefits -->

<!-- Begin Garden Membership Policies -->
	<div class="col-sm-6 lowpadding">
	
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#mempolicies" data-toggle="collapse">Garden Membership Policies</button>
		</span>
		
		<div class="collapse" id="mempolicies">
			<br />
			
			<h3>Garden Membership Policies</h3>
			
			<ul>
				<li>Memberships are non-refundable and non-transferable.</li>
				<li>Member events, programs, and discounts apply to cardholders only.</li>
				<li>Cardholder must be present to receive benefits. Photo ID may be required.</li>
				<li>Unlimited General Admission does not include concerts, Garden After Dark, or other separately ticketed events.</li>
				<li>Garden-Plus is the only membership level that allows for a guest to be named as a cardholder. All other levels have set cardholder allowances.</li>
				<li>You may apply same-day admission costs to the purchase of a membership. Offer is only available at the Visitor Center desk on the day that admission to the Garden was purchased.</li>
				<li><span style="color:#FF0000;font-weight:bold;font-style:italic;">Membership purchase does not guarantee Red Butte Garden Outdoor Concert Series tickets or access to other ticketed events.</span></li>
				<li>Only Garden-Plus Membership level and above receive member-rate concert tickets and member-only presale period access to the Red Butte Garden Outdoor Concert Series.</li>
				<li>The American Horticultural Society’s <a href="http://www.ahsgardening.org/rapgardens" target="_blank">Reciprocal Admissions Program</a> offers free admission and/or additional benefits at 300 gardens throughout North America and the Cayman Islands. Institutions less than 90 miles away from Red Butte Garden or your residence are not included. Photo ID may be required for entry.</li>
				<li><span style="color:#FF0000;font-weight:bold;font-style:italic;">Member Benefits are subject to change without notice.</span></li>
			</ul>
			
			<br/>
			
			<center>
				<h4>More Questions?</h4>
				<p><b>See the <a href="/membership-FAQ">Membership FAQs</a></b></p>
			</center>
			
			<br />
		
		</div>
			
	</div>
<!-- End Garden Membership Policies -->

</div>

<!-- Begin Individual Memberships -->

	<h2>Membership Levels</h2>

	<div class="row">
	
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
					<!-- <div class="memsprite01"></div> -->
				<img src="/images/misc/membership-01.jpg" class="responsive" />
				</div>
				
				<div class="meminfo">
				
					<h4>Garden-Basic Membership</h4>
					<h5>$40 - Great for Garden-lovers!</h5>
					
					<ul>
						<li>Member benefits for one individual</li>
						<li>This level does not include concert benefits</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=1873EC10-CFCC-47FA-8127-DCF40E76B7ED">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-02.jpg" class="responsive" />
				<!--	<div class="memsprite02"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Garden-Plus Membership</h4>
					<h5>$55 - Best for concert-goers!</h5>
					
					<ul>
						<li>Member benefits for one individual</li>
						<li>Garden admission for one guest, or the ability to add a second cardholder</li>
						<li>This level may purchase two discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=A915DE52-EEA3-4F58-8F19-1B211486EC2E">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
	</div>

	<div class="row">
	
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
					<img src="/images/misc/membership-03.jpg" class="responsive" />
				</div>
				
				<div class="meminfo">
				
					<h4>Family Membership</h4>
					<h5>$75 - Great for parents or grandparents!</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for up to six children age 17 and under</li>
						<li>This level may purchase four discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=D886CE48-6C4C-4706-9A77-D7A81BB1AAB1"><input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" /></a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-04.jpg" class="responsive" />
				<!--	<div class="memsprite04"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Family-Plus Membership</h4>
					<h5>$105 - Great for parents and caretakers!</h5>
					
					<ul>
						<li>Member benefits for three individuals</li>
						<li>Garden admission for up to six children age 17 and under</li>
						<li>This level may purchase four discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=4AD22372-1557-49F1-BD47-43BB15D3E0F1">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
	</div>
	
		<div class="row">
	
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-05.jpg" class="responsive" />
				<!--	<div class="memsprite05"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Circle of Friends Membership</h4>
					<h5>$80 - Great for the entertainer!</h5>
					
					<ul>
						<li>Member benefits for one individual</li>
						<li>Garden admission for three guests</li>
						<li>This level may purchase four discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=0460BACD-643D-490E-840C-57CD48A87CC5">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-06.jpg" class="responsive" />
				<!--	<div class="memsprite06"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Contributor Membership</h4>
					<h5>$150 - Best Value!</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for six guests</li>
						<li>This level may purchase six discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=43687013-E419-49C6-9EB4-246DDA0D0546">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
	</div>
	
	<br />
	
	<h2>Giving Circle Membership Levels</h2>
	
	<div class="row">
	
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-07.jpg" class="responsive" />
				<!--	<div class="memsprite07"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Forget-Me-Not Membership</h4>
					<h5>$250</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for up to eight guests</li>
						<li>This level may purchase six discounted tickets per concert</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=0055B912-8CE6-4030-9767-76AEF0E244CA">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-08.jpg" class="responsive" />
				<!--	<div class="memsprite08"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Blazing Star Membership</h4>
					<h5>$500</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for eight guests</li>
						<li>This level may purchase eight discounted tickets per concert</li>
						<li>Garden tour with a Garden staff member</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=414DA095-7C21-471C-A0B1-66900D435ABE">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		
	</div>
	
	<div class="row">
	
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
				<img src="/images/misc/membership-09.jpg" class="responsive" />
				<!--	<div class="memsprite09"></div> -->
				</div>
				
				<div class="meminfo">
				
					<h4>Avant Gardener Membership</h4>
					<h5>$1000</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for eight guests</li>
						<li>This level may purchase eight discounted tickets per concert</li>
						<li>Garden tour with the Garden's Executive Director</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=29E5CB61-3526-455C-8DFF-9A674712213D">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>		
		
		<div class="col-sm-6 lowpadding">
			
			<div class="memwrap">
				
				<div class="mempic">
					<img src="/images/misc/membership-10.jpg" class="responsive" />
				</div>
				
				<div class="meminfo">
				
					<h4>Director's Club Membership</h4>
					<h5>$2500</h5>
					
					<ul>
						<li>Member benefits for two individuals</li>
						<li>Garden admission for eight guests</li>
						<li>This level may purchase eight discounted tickets per concert</li>
						<li>Exclusive behind the scenes Garden tour with the Garden's Executive Director</li>
					</ul>
					<a href="https://55218.blackbaudhosting.com/55218/Garden-Membership?mpl=A66A35DF-0860-45A2-8233-50849C32D351">
						<input type="submit" name="Membership-button" value="Buy or Renew" class="membutton" />
					</a>
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
				
	</div>
<!-- End Individual Memberships -->

<br />

<!-- Begin Corporate & Organization Memberships -->
	<h2>Corporate &amp; Organization Memberships</h2>
		
	<div class="row">
	
		<div class="col-md-4 lowpadding">
			
			<div class="memwrap">
				
				<div class="meminfo memcorp">
				
					<h4>Horticulture Therapy Pass</h4>
					
					<div>Red Butte Garden is a great place to host breakouts and meetings, or simply bring your employees to find a little piece of mind. Horticulture Therapy Passes are perfect for non-profits who frequent the Garden.</div>
					<br />
					<p><b>To find out more:</b></p>
					<ul>
						<li>Call: <b>(801) 585-7172</b></li> 
						<li>Email: <a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a></li>
					</ul>

				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
		<div class="col-md-4 lowpadding">
			
			<div class="memwrap">
				
				<div class="meminfo memcorp">
				
					<h4>Corporate Memberships</h4>
					
					<p><a href="/corporate-memberships"><b>Customize a Program</b></a> for your company.</p>
					
					<p><b>To find out more:</b></p>
					<ul>
						<li>Call: <b>(801) 585-7172</b></li> 
						<li>Email: <a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a></li>
					</ul>

					<p><b>Outdoor Concert Series Sponsorships</b></p>
Is your company interested in concert tickets?<br/>
<a href="/donor-ticket-packages">Find out more about Donor Ticket Packages.</a></p>
					
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>
		
	
		<div class="col-md-4 lowpadding">
			
			<div class="memwrap">

				<div class="meminfo memcorp">
				
					<h4>Corporate Matching Gifts</h4>

					<p>Did you know that many corporations offer employee giving programs where they match donations to Red Butte Garden? If you volunteer at the Garden, your company may also offer a volunteer grant program. To double the impact of your gift, check the <a href="http://giving.utah.edu/ways-to-give/">University of Utah Office of Development</a> website to see if your company offers a matching gift program or contact your employers' Human Resources Department.</p>
					
				<!--This is a swag.-->
				</div>
				
			</div> 
			
		</div>		
				
	</div>
<!-- End Corporate & Organization Memberships -->



</div>

<!-- Begin Membership FAQ Link / Contact Info -->

<br />
<div class="row">
	<div class="col-xs-12 lowpadding">
		<div class="memfaqwrap">
			<a href="/membership-FAQ"><div class="memfaq">Membership FAQ</div></a>
		</div>
	</div>
</div>
<br />	
<center>
	<h5>Additional Questions?</h5>
	<p>Please Email <a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a> or Call <b>(801) 585-7172</b></p>
</center>
<!-- End Membership FAQ Link / Contact Info -->

<!-- How much Swag could a WoodSwag Swag if a WoodSwag could Swag Wood? -->
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