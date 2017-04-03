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
<title>Local Retail Partners</title>
    

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
        <h1 class="text-center">Members Only Discounts at Local Retail Partners</h1>

<br />

<h4 class="text-center green">Red Butte Garden Members receive 10%-20% off your purchase with our Retail Partners year-round.</h4>

<h5 class="text-center">See a complete list of these generous partners below. Visit their website to learn about their services and their shops to collect your discount!</h5>

<br />
	<div class="memfaqwrap lowpadding">
		<a href="/memberships"><div class="memfaq">BUY OR RENEW MEMBERSHIP</div></a>
	</div>
<br />	

<div class="row-fluid text-center">

	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Babinski’s Baby</h3>
		
		<h6>1324 Foothill Drive, Salt Lake City - (801) 583-2229</h6>
		<h6>8920 South State Street, Sandy - (801) 892-2300</h6>
		<h6><a href="www.babinskis.com">www.babinskis.com</a></h6>
		
		<p>A unique baby boutique featuring everything for your special little one. Clothing, cribs, toys, strollers, and so much more!</p>
		
		<p class="bold">10% off any one regularly priced clothing item</p>
	
	</div>

	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">The Bar Method Salt Lake</h3>
		
		<h6>1057 East 2100 South, Salt Lake City - (801) 485-4227</h6>
		<h6></h6>
		<h6><a href="www.saltlakecity.barmethod.com">www.saltlakecity.barmethod.com</a></h6>
		
		<p>The Bar Method is an efficiently designed exercise that combines every aspect important to your fitness. It builds strength, increases flexibility, improves posture, and burns calories.</p>
		
		<p class="bold">25% discount on a five-class punch pass (redeem discount at the studio - not available online)</p>
	
	</div>

	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Butterfield Gardens II, Inc.</h3>
		
		<h6>9119 South Monroe Plaza Way, Sandy - (801) 381-2593</h6>
		<h6></h6>
		<h6><a href="www.butterfieldgardens.com">www.butterfieldgardens.com</a></h6>
		
		<p>Offering 140 varieties of ground cover that are garden ready and Utah hardy.</p>
		
		<p class="bold">10% discount off full flats</p>
	
	</div>

</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Cactus & Tropicals</h3>
		
		<h6>2735 South 2000 East, Salt Lake City - (801) 485-2542</h6>
		<h6>12252 South Draper Gate Dr. (1325 East), Draper - (801) 676-0935</h6>
		<h6><a href="www.cactusandtropicals.com">www.cactusandtropicals.com</a></h6>
		
		<p>Potted blooming and tropical plants, annuals, perennials, and flowering shrubs.</p>
		
		<p class="bold">10% discount on products</p>
	
	</div>

	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Desert Water Gardens</h3>
		
		<h6>3674 South 900 East, Salt Lake City - (801) 270-0939</h6>
		<h6></h6>
		<h6><a href="www.desertwatergardens.com">www.desertwatergardens.com</a></h6>
		
		<p>Specializing in the design, construction, and maintenance of garden ponds. Featuring new aquaponics supplies this year. Providing “How To” seminars to ensure that you “do it right the first time.”</p>
		
		<p class="bold">10% off</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Garage On Beck</h3>
		
		<h6>1199 Beck Street, Salt Lake City - (801) 521-3904</h6>
		<h6 class="red">MUST BE 21+</h6>
		<h6><a href="www.garageonbeck.com">www.garageonbeck.com</a></h6>
		
		<p>The Garage On Beck is a roadhouse bar and grill music venue located on the edge of Salt Lake City. Best patio in town!</p>
		
		<p class="bold">15% off food purchases (Not good with any other offer)</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Glover Nursery</h3>
		
		<h6>9275 S 1300 W, South Jordan - (801) 562-5496</h6>
		<h6></h6>
		<h6><a href="www.glovernursery.com">www.glovernursery.com</a></h6>
		
		<p>Glover Nursery has been in the nursery business for over 100 years! We offer "retail ready" plant material of all varieties of shrubs, trees, conifers, perennials and annuals. We have a great selection of bulk products as well as a pond department featuring "pondless" water features.</p>
		
		<p class="bold">10% discount off all non sale items</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Gold ‘n Diamonds</h3>
		
		<h6>1318 Foothill Drive, Salt Lake City - (801) 582-0232 </h6>
		<h6></h6>
		<h6><a href="www.goldndiamondsaltlake.com">www.goldndiamondsaltlake.com</a></h6>
		
		<p>Third-generation jewelers. Offering gold and platinum jewelry, diamonds, colored stones, and Citizen watches. Jewelry and watch repair.</p>
		
		<p class="bold">20% discount</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Haroons</h3>
		
		<h6>1326 A Foothill Drive, Salt Lake City - (801) 583-1685</h6>
		<h6></h6>
		<h6><a href="www.haroons.com">www.haroons.com</a></h6>
		
		<p>Let this boutique put together your dream outfit for a wedding or to pair with your favorite jeans! Our unique and timeless jewelry, accessories, and clothing with lovely handwork, keep step with the latest fashions and trends.</p>
		
		<p class="bold">10% off on regularly priced items</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Home & Yard Pottery "The Pot Shop"</h3>
		
		<h6>8610 S State Street, Salt Lake City - (801) 567-1255</h6>
		<h6>598 North Bluff, St. George (435) 656-2151</h6>
		<h6><a href="www.bigpotshop.com">www.bigpotshop.com</a></h6>
		
		<p>A Utah treasure with the largest selection of high-fired pottery, fairy garden supplies, and outdoor decorations. Water fountains and fire pots custom made from beautiful pots you pick out. No other outdoor yard decoration store like us, great selection, value and price.</p>
		
		<p class="bold">10% discount</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Millcreek Gardens</h3>
		
		<h6>3500 South 900 East, Salt Lake City - (801) 487-4131</h6>
		<h6></h6>
		<h6><a href="www.millcreekgardens.com">www.millcreekgardens.com</a></h6>
		
		<p>Utah's favorite garden center for over 60 years with an outstanding variety of plants and garden supplies.</p>
		
		<p class="bold">10% discount (Excludes bulk and sod items)</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Northern Electric Company, Inc.</h3>
		
		<h6>3414 South 300 West, Salt Lake City - (801) 466-1672</h6>
		<h6></h6>
		<h6><a href="www.northernelectriccompany.com">www.northernelectriccompany.com</a></h6>
		
		<p>Experienced and caring electricians repairing and remodeling Wasatch Front homes and businesses since 1995. With NEC you get free estimates, a 2-year trouble-free warranty, and an A+ rating from the BBB.</p>
		
		<p class="bold">$20 discount on a one-hour repair or service call or a 5% discount on jobs greater than $500.</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Peak Performance Automotive - Subaru Specialists</h3>
		
		<h6>2810 South 400 West, Salt Lake City - (801) 446-8600</h6>
		<h6></h6>
		<h6><a href="#"></a></h6>
		
		<p>Automotive service and repair on all makes and models – especially Subarus!</p>
		
		<p class="bold">$25 one-time discount good for any service $100 or more</p>
		<p class="bold">$28 for Safety & Emission testing for 1996 and newer vehicles. $35 for 1995 and older.</p>
		<p class="bold">Free check engine light check for 1996 and newer vehicles.</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Red Butte Café</h3>
		
		<h6>1414 Foothill Drive, Salt Lake City - (801) 581-9498</h6>
		<h6></h6>
		<h6><a href="www.theredbuttecafe.com">www.theredbuttecafe.com</a></h6>
		
		<p>A local favorite since 1991. The menu includes an inspired selection of seasonal entrees that change every two weeks. Desert Edge brews beer on tap and bakes signature cakes and tarts in-house.</p>
		
		<p class="bold">Two-for-One desserts by the slice</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Red Butte Garden Gift Shop</h3>
		
		<h6>300 Wakara Way, Salt Lake City - (801) 585-0556</h6>
		<h6></h6>
		<h6><a href="www.redbuttegarden.org/gift-shop">www.redbuttegarden.org/gift-shop</a></h6>
		
		<p>Offering a great selection of locally made products and a wide variety of garden-inspired gifts.</p>
		
		<p class="bold">10% discount</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Rimini Coffee</h3>
		
		<h6>532 South 400 West, Salt Lake City - (801) 539-1210</h6>
		<h6></h6>
		<h6><a href="www.riminicoffee.com">www.riminicoffee.com</a></h6>
		
		<p>One of Salt Lake City’s favorite neighborhood coffee shops. Featuring Great Harvest Breads, Rico’s Burritos, and Rimini Coffee all baked, prepared and roasted in Salt Lake City. Rimini was voted Best of Utah Coffee Beans by City Weekly in 2013.</p>
		
		<p class="bold">10% discount</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Sax-Romney Florist</h3>
		
		<h6>1549 South 1100 East, Suite D, Salt Lake City - (801) 487-2179</h6>
		<h6></h6>
		<h6><a href="www.saxromney.com">www.saxromney.com</a></h6>
		
		<p>Full-service florist specializing in unique designs, high quality and friendly customer service. If you can think of it we can deliver!</p>
		
		<p class="bold">10% discount and $6.00 Delivery (Clearance, sale items and gift cards excluded)</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Scentsations Lotions and Oils</h3>
		
		<h6>1316 Foothill Drive, Salt Lake City - (801)364-0168</h6>
		<h6></h6>
		<h6><a href="www.scentsationslotionsoils.com">www.scentsationslotionsoils.com</a></h6>
		
		<p>We have what your skin needs! Aromatherapy products, lotions, oils, massage oils, breezy sleepwear, perfumes, essential oils, natural body and hair care products for men and women.</p>
		
		<p class="bold">10% off entire purchase</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Spa Club</h3>
		
		<h6>1400 Foothill Drive #160, Salt Lake City - (801)255-3655</h6>
		<h6></h6>
		<h6><a href="www.thespaclub.com">www.thespaclub.com</a></h6>
		
		<p>Full service day spa and salon offering facials, massage, manicures, pedicures, waxing, and a full-service hair salon. Spa members receive prices that are 10%-60% off spa services.</p>
		
		<p class="bold">Guest pass for spa members and one complimentary skin freshener.</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Stoneground Kitchen</h3>
		
		<h6>249 East 400 South, Salt Lake City - (801)364-1368</h6>
		<h6></h6>
		<h6><a href="www.stonegroundslc.com">www.stonegroundslc.com</a></h6>
		
		<p>Offers an urban-chic, warm, inviting atmosphere and a well versed menu of New York style pizzas, pastas, salads, sandwiches, soups, and award-winning tiramisu. Now offering Sunday brunch.</p>
		
		<p class="bold">10% off food purchases (Not good with any other offer).</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Sugar House Coffee</h3>
		
		<h6>2011 South 1100 East, Salt Lake City - (801) 883-8867</h6>
		<h6></h6>
		<h6><a href="www.sugarhousecoffee.com">www.sugarhousecoffee.com</a></h6>
		
		<p>Salt Lake City’s "Best Neighborhood Coffee Shop." Sugar House Coffee has been providing the community with a public gathering space since 2002. Locally sourced ingredients make the menu memorable.</p>
		
		<p class="bold">10% discount</p>
	
	</div>
	
</div>
	
<div class="row-fluid text-center">
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">The Tutoring Toy</h3>
		
		<h6>1400 Foothill Drive, Salt Lake City - (801) 581-1060</h6>
		<h6></h6>
		<h6><a href="www.tutoringtoy.com">www.tutoringtoy.com</a></h6>
		
		<p>Toys That Spark Imagination And Growth.</p>
		
		<p class="bold">15% off any one item (Not combinable)</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Twigs Flower Company</h3>
		
		<h6>1616 South 1100 East, Salt Lake City - (801) 596-2322</h6>
		<h6></h6>
		<h6><a href="www.twigsflowerco.com">www.twigsflowerco.com</a></h6>
		
		<p>Voted “Best Roses in Utah” by Salt Lake Magazine five years in a row. Beautiful flowers for all occasions.</p>
		
		<p class="bold">20% discount (Not good with any other sale or promotion)</p>
	
	</div>
	
	<div class="col-sm-4 local-retail-partner">
		
		<h3 class="green">Wildflowers – A Bed and Breakfast</h3>
		
		<h6>936 East 1700 South, Salt Lake City - (801) 466-4728</h6>
		<h6></h6>
		<h6><a href="www.wildflowersbb.com">www.wildflowersbb.com</a></h6>
		
		<p>A bed and breakfast offering comfortable night stays, gourmet breakfasts, and warm personal service.</p>
		
		<p class="bold">10% discount (Reservations required)</p>
	
	</div>

</div>

<br />
	<div class="memfaqwrap lowpadding">
		<a href="/memberships"><div class="memfaq">BUY OR RENEW MEMBERSHIP</div></a>
	</div>
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