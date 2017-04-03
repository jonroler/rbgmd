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
<title>Gardening in Utah</title>
    

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
		<div class="grid-header">GARDENING IN UTAH</div>		
	<hr>
</div>

<br />

<div class="row">

	<div class="col-sm-4">

		<img src="/images/misc/staff-gardening-02.jpg" class="responsive" alt="Red Butte Staff Gardening" title="Red Butte Staff Gardening">
		<br class="br-hide-lg" />
		
	</div>

	<div class="col-sm-4">

		<img src="/images/misc/staff-gardening-03.jpg" class="responsive" alt="Red Butte Staff Gardening" title="Red Butte Staff Gardening">
		<br class="br-hide-lg" />

	</div>

	<div class="col-sm-4">

		<img src="/images/misc/staff-gardening-05.jpg" class="responsive" alt="Red Butte Staff Gardening" title="Red Butte Staff Gardening">
		<br class="br-hide-lg" />

	</div>

</div>

<br />

<div class="row">

			<div class="col-sm-12">

				<span class="no-button-outline">
					<button class="volbutton hover green-bg" data-target="#gardening-articles" data-toggle="collapse">GARDENING &amp; WATERWISE ARTICLES</button>
				</span>

				<div class="collapse panel-border" id="gardening-articles">
					
					<br />

				<div class="row-fluid">
					
					<div class="col-xs-12">
						
						<br />
						
						<p class="text-center">Red Butte Garden is maintained by skilled and talented horticulture experts who understand the difficulties associated with gardening, especially in a climate such as Utah’s. Because of this, the garden’s staff is more than willing to share their knowledge and answer the many questions that come their way. Based on many common gardening concerns, here is a list of helpful tips and advice from the Red Butte Garden Horticulture Staff.</p>
					
					</div>
					
					<!-- BEGIN GARDENING ARTICLES PANEL -->
					
					<div class="col-sm-4">
					
						<h4 class="green">Regional and Seasonal Gardening</h4>
						
						<ul>
							<li><a href="/create-year-round-interest-in-your-garden">Create Year-Round Interest in Your Garden</a></li>
							<li><a href="/gardening-in-salt-lake">Gardening in Salt Lake</a></li>
							<li><a href="/herbs-for-utah-gardens">Herbs for Utah Gardens</a></li>
							<li><a href="/microclimates">What is a Microclimate?</a></li>
							<li><a href="/spring-blooming-bulbs">Spring Blooming Bulbs (Besides Daffodils and Tulips)</a></li>
						</ul>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="green">Advice on...</h4>
						
						<ul>
							<li><a href="/fertilizing-your-garden">Fertilizing Your Garden</a></li>
							<li><a href="/mulching">Mulching</a></li>
							<li><a href="/pruning-101">Pruning 101</a></li>
							<li><a href="/selecting-a-qualified-arborist">Selecting a Qualified Arborist</a></li>
							<li><a href="/selecting-the-right-tree">Selecting the Right Tree</a></li>
							<li><a href="/tree-selection-near-powerlines">Tree Selection Near Powerlines</a></li>
							<li><a href="/tree-stump-removal">Tree Stump Removal</a></li>
							<li><a href="/vegetable-gardens-in-small-places">Vegetable Gardens in Small Places</a></li>
						</ul>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="green">Insects/Pests</h4>
						
						<ul>
							<li><a href="/ants-on-my-plants">Ants on my Plants</a></li>
							<li><a href="/beneficial-bugs">Beneficial Bugs</a></li>
							<li><a href="/boxelder-bugs">Boxelder bugs</a></li>
							<li><a href="/earthworms">Earthworms</a></li>
							<li><a href="/mule-deer">Mule Deer</a></li>
							<li><a href="/slugs-and-snails">Slugs and snails</a></li>
						</ul>
						
					</div>
					
				</div>

				<div class="row-fluid">
					
					<div class="col-sm-4 tan-bg">
						
						<h4 class="green">Conditions</h4>
						
						<ul>
							<li><a href="/iron-chlorosis">Iron Chlorosis</a></li>
							<li><a href="/planting-in-the-shade">Planting in the Shade</a></li>
							<li><a href="/waterwise-and-xeric-gardening">Waterwise and Xeric Gardening</a></li>
						</ul>
						
					</div>
					
					<div class="col-sm-4">
						
						<h4 class="green">References</h4>
						
						<ul>
							<li><a href="/horticulture-references">Horticultural References</a></li>
							<li><a href="/native-plant-reference-books">Native Plant Reference Books</a></li>
						</ul>
						
					</div>
						
					<!-- END GARDENING ARTICLES PANEL -->
				</div>	
	
			<br />
		
		</div>
			
	</div>

</div>

<br class="br-hide" />
	
<div class="row">	
	<!-- BEGIN MONTHLY GARDENING TIPS PANEL -->
	<div class="col-sm-12">
		
		<span class="no-button-outline">
			<button class="volbutton hover" data-target="#gardening-tips" data-toggle="collapse">MONTHLY GARDENING TIPS</button>
		</span>
		
		<div class="collapse panel-border" id="gardening-tips">
			
			<br />
		
			<div class="panel-group" id="gardeningaccordion">
					 
			<div class="row">
				<div class="col-sm-6">

					<!-- January Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#jan-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143">
					        <div class="panel-title">
					        	<p class="text-center white">JANUARY</p>
					        </div>
						</div>
					  </a>
					  <div id="jan-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
								<div class="col-sm-12">
								
							    	<hr width="50%" style="background-color:#158FBF;" />
							    	
							    	<br />
							    
									<p>If you want your amaryllis to bloom again next year follow these simple steps:</p>
									
									<p>After blooming cut back the flower spike close to the base of the bulb. The leaves should be left intact since they are making food for next year's flowers. Place in bright light and continue to water and fertilize monthly. After last frost in spring, you can move your amaryllis outdoors for the summer. Continue to water and fertilize. Mid September allow the soil to completely dry, cut back the foliage and place the bulb in a paper bag and store in a cool dark area for a rest period of 6 - 8 weeks. After the rest period you can repot the amaryllis bulb and it should bloom again in 10 - 12 weeks.</p>
									
									<p>Plant paperwhite bulbs every other week for continuous flowers.</p>
									
									<p>Birds will welcome both food and water during freezing temperatures and when the ground is covered with snow. You might even consider purchasing a water-heater designed to keep birdbaths free of ice.</p>
									
									<p>Send your Christmas tree to the local recycle center so the tree can be shredded into mulch for use in the garden, or put it in the yard so birds can use the tree as a habitat. Add some pinecones smeared with peanut butter or other bird delectables and you've got a natural bird feeder.</p>
									
									<p>Prevent evergreen branches from breaking by shaking or brushing off heavy wet snow.</p>
									
									<p>This is a good time to order seeds from catalogues so you will be ready for planting when the weather permits.</p>
									
									<p>If de-icers are used on icy walks and driveways, use products that will not harm turf grasses and other plants.</p>
									
									<p>Got the winter-time blues? Take a short trip to your local nursery or greenhouse to see something green, growing, and in flower.The Orangerie at Red Butte Garden is a great place to relax, enjoy the view of the city and the unique plants growing there.</p>
									
									<br />
									
									<hr width="50%" style="background-color:#158FBF;" />
							
								</div>
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />

				<div class="col-sm-6">
					<!-- February Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#feb-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">FEBRUARY</p>
					        </div>
						</div>
					  </a>
					  <div id="feb-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
					    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#158FBF;" />
							    	
							    	<br />
								
									<p>This is the time of year to plan for spring and summer planting.Think water-wise or drought tolerant plants.There are a large number of trees, shrubs, perennials and even some annuals that will grow with less water. See your nursery professional or horticulturist for their recommendations. Starting in April the Garden will be offering numerous classes, workshops and other native plant events. Some of which are about water- wise techniques and drought tolerant plants.</p>
									
									<p>Continue to water broadleaf evergreens to prevent leaves from drying out during periods of bright sunshine or windy conditions.</p>
									
									<p>Want a breath of spring? Force branches into early bloom such as forsythia, cherry, quince, plum, eastern redbud, lilac, magnolia, serviceberry or other early flowering trees and shrubs. Place the cut branches in water in a bright, sunlit place to trigger early flowering.</p>
									
									<p>Even without snow to cover their food sources, birds will continue to enjoy supplemental food and water, so keep birdfeeders and water troughs filled.</p>
									
									<p>Late February is usually the best time to prune most fruit trees. For information on how to prune specific fruit varieties, seek professional advice from <em>Utah State University Extension</em> at <strong>468-3170-ext. 1</strong>.</p>
									
									<p>Now is a good time to start indoor seeds for later, outdoor planting. And if you want to know more about starting plants from seed and have fun at the same time, enroll in RedButte Garden's spring propagation workshop. Check our Calendar for upcoming Classes.</p>
							
									<br />
									
									<hr width="50%" style="background-color:#158FBF;" />
							
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>

			<br />
			
			<div class="row">
				<div class="col-sm-6">	
					<!-- March Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#mar-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">MARCH</p>
					        </div>
						</div>
					  </a>
					  <div id="mar-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
					    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#A26BA2;" />
							    	
							    	<br />
					    
									<p>Prune trees and shrubs that were damaged by heavy snow. It's also a good time to plant trees. Check out our classes "Unique Trees for Utah Landscapes" and/or "Fabulous Fruit Trees" this spring.</p>
									
									<p>Cut back ornamental grasses and perennials that weren't pruned in the fall.</p>
									
									<p>Start seeds of vegetables and annual flowers indoors under fluorescent lights for late May - June planting outdoors.</p>
									
									<p>Core aerate lawn area if heavily compacted once soil dries.</p>
									
									<p>Apply pre-emergent herbicide for crab grass control between March 15 - April 15.</p>
									
									<p>Cool season vegetables like peas, radish, lettuce, and spinach can be planted as soon as the soil can be worked. Transplants of cool season vegetables like broccoli and cabbage can also be planted as soon as soil can be worked.</p>
									
									<p>Quality soil is the foundation for plants, have soil tested before planting new areas. Soil tests will give you important information like pH, % organic matter, soluble salts, and major nutrients in soil. Recommendations for amendments will also be provided. Soil tests can be obtained from USU Extension.</p>
									
									<p>Design a section of your landscape to be more water efficient. Join us for one of our many water-wise and native plant classes, including "Irrigation Basics" or "Residential Landscape Design."</p>
									
									<p>Plant bare root roses the latter part of the month, soak roots of bare root roses in water several hours before planting</p>
									
									<p>Prune hybrid tea and shrub roses late March to early April removing dead and diseased wood, and crossing branches. Cut remaining branches of hybrid teas back to 16 - 24 inches above ground level. Join the "Rose Pruning Workshop" for hands-on experience.</p>
									
									<p>Force branches of Pussy Willow, Cherry, Quince, and Forsythia to bloom indoors. Prune twigs once flower buds are swollen, place in vase of water and put in sunny warm location.</p>
									
									<br />
									
									<hr width="50%" style="background-color:#A26BA2;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />
				
				<div class="col-sm-6">
					<!-- April Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#apr-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">APRIL</p>
					        </div>
						</div>
					  </a>
					  <div id="apr-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
					    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#A26BA2;" />
							    	
							    	<br />
					    
									<p>April is one of the busiest months in the garden. Here are a few tips for what to do in the garden this month:</p>
									
									<p>Start warm season vegetables and flowers indoors under fluorescent lights for transplanting outdoors mid May after the last frost. Peppers, eggplant, cucumber, squash, and melons can be started indoors now.</p>
									
									<p>Cool season vegetables like peas, radishes, lettuce, spinach can be planted now.</p>
									
									<p>Cut back ornamental grasses to within 2 - 3 inches of the ground, if this wasn't done in March. Cut back herbaceous perennials that weren't cut back in the fall.</p>
									
									<p>Convert a small section of your landscape to drought tolerant plants. Learn more about waterwise landscaping in our short course in April. Check the calendar for details.</p>
									
									<p>Plant trees, shrubs, perennials, and cool season annuals like pansies. Divide and transplant perennials that have become overgrown.</p>
									
									<p>Prune out winter damaged branches and twigs from ornamental plants.</p>
									
									<p>Cool season turf grasses like Kentucky Bluegrass will start to green up. This is a good time to aerate lawns and fertilize using a nitrogen fertilizer. Apply preemergent herbicide to lawn areas to control crabgrass.</p>
									
									<p>Prune hybrid tea roses before they leaf out. Wait to prune climbing and shrub roses until after they bloom.</p>
									
									<p>Check irrigation system for problems.</p>
									
									<p>Deadhead spring blooming bulbs such as daffodils, crocus and tulips but don't cut back leaves until they start to yellow. Check out the beautiful display of blooming bulbs in the Four Seasons Garden at Red Butte Garden this Spring.</p>
							
									<br />
									
									<hr width="50%" style="background-color:#A26BA2;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>

			<br />
			
			<div class="row">

				<div class="col-sm-6">	
					<!-- May Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#may-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">MAY</p>
					        </div>
						</div>
					  </a>
					  <div id="may-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
					    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#A26BA2;" />
							    	
							    	<br />
					    
									<p>Prune spring-flowering shrubs such as forsythia, lilac, and quince, as soon as the bloom is finished. Remove older stems, broken, dead, or crossing branches.</p>
									
									<p>Watch for aphids on new growth of roses, perennials, and spiraea. Spray them with a strong stream of water or use an insecticidal soap to control the insects.</p>
									
									<p>Plant trees, shrubs, and perennials obtained from the nursery now. The cool weather and spring rain we usually receive is optimal for new plants.</p>
									
									<p>It is not too late to apply a pre-immergent herbicide to control crabgrass and other annual weeds. Be careful not to use the chemical on vegetable garden or flower beds that will be seeded later as the weather warms.</p>
									
									<p>Cut the spent flowerheads of spring flowering bulbs such as daffodils and tulips. Do not cut back the leaves of these plants until the foliage begins to fade and turn brown since the bulbs need the food produced by the leaves to feed the bulb for next year's bloom.</p>
									
									<p>After the first grass mowing of the season, raise mower blades to their proper cutting height. For Kentucky bluegrass and other cool season turf grasses, that is from 2" to 3" inches high. Keeping the turf grass at this height will promote root growth, conserve water, reduce weeds, and provide for a healthier lawn.</p>
									
									<p>Mulch bare ground to conserve moisture and control weeds.</p>
									
									<p>It is not too late to aerate lawns to improve supply of air, water, and nutrients to turf root systems. Power raking should only be done where extreme amounts of thatch have built up in the turf.</p>
									
									<p>As soon as garden beds are dry enough to allow working the soil, apply and dig in compost or peat moss to increase water-holding ability.</p>
									
									<p>Begin setting out hardier potted plants such as geraniums on decks, porches, and patios. Wait until danger of frost is past to pot-up other tender, less hardy plants. Want to learn about native plants for water conservation, perennial and herb care, or how to use stone in the landscape? Check out our May <a href="/calendar">CALENDAR</a> for useful classes!</p>
									
									<br />
									
									<hr width="50%" style="background-color:#A26BA2;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />

				<div class="col-sm-6">
					<!-- June Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#jun-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">JUNE</p>
					        </div>
						</div>
					  </a>
					  <div id="jun-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
						    <div class="row-fluid">
						    	
									<div class="col-sm-12">
									
										<hr width="50%" style="background-color:#196143;" />
								    	
								    	<br />
						    
										<p>Conserve water by watering lawns only before 10:00am or after 6:00pm.</p>
										
										<p>Set out all warm season vegetable and annual flower seedlings or plant seeds now.</p>
										
										<p>Watch for slug and snail damage on plants and use prepared bait or other techniques to control the pests.</p>
										
										<p>Continue to apply mulch to garden and vegetable beds. The mulch will help to conserve water and improve soil texture as the mulch decomposes.</p>
										
										<p>Trim dead and dying leaves of spring flowering bulbs.</p>
										
										<p>Grasshopper damage will begin to show on tender young plants. If insecticides are used for control, make sure that directions are closely followed to prevent harm to bees and other beneficial insects.</p>
										
										<p>As summer temperatures climb, don't over-fertilize cool season turf grasses. These grasses perform best during cooler weather, and applying fertilizer in mid summer heat does not benefit turf development.</p>
										
										<p>Control annual weeds before they mature to prevent them from setting and dispersing seed.</p>
										
										<p>Visit Red Butte Garden to see the variety of plants that are in flower during this time of year and take advantage of the many classes we have to offer.</p>
										
										<p>Want to learn about native plants for water conservation, perennial and herb care, or how to use stone in the landscape? Check out our <a href="/calendar">CLASS CALENDAR</a> for useful classes!</p>
										
										<br />
										
										<hr width="50%" style="background-color:#196143;" />
										
									</div>
									
						    </div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>

			<br />
				
			<div class="row">

				<div class="col-sm-6">	
					<!-- July Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#jul-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">JULY</p>
					        </div>
						</div>
					  </a>
					  <div id="jul-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#196143;" />
							    	
							    	<br />
					    
									<p>What a great time to be out enjoying the garden and the rewards of all your spring toils. Your garden is full of blossoms and greenery. Barefoot breakfasts on the deck and warm summer evening festivities bring needed respite to our busy lives.</p>
									
									<p>A great way to enjoy your garden is by cutting flowers early in the morning and arranging them for indoor display.</p>
									
									<p>Many flowers are also edible and can dress up your table. Pineapple sage (sweet), nasturtium (peppery), and daylily flowers are all quite tasty.</p>
									
									<p>Keeping gardens and containers watered this time of year becomes a daily challenge. Watering early in the day or in late evening will help the water soak into the soil instead of evaporating. Do not water between the hours of 10:00 am and 6:00 pm.</p>
									
									<p>For automated sprinkler systems this is a good time to see how it is working. Examine each head to see if they are broken or clogged and to make sure heads are turned in the right direction to spray on the flowerbeds. Often we forget about them because they run so early in the morning. If overspray is a problem, often a few turns of the screw in the middle of most heads with shorten the spray distance. If you live in a managed property, let the management company know if you see a broken head.</p>
									
									<p>As plants grow, garden pests and weeds will challenge even the most persistent gardener. Scheduling a specific time or certain number of hours per week to be in your garden can help you keep weeds in check or notice pest problems. Removing younger weeds before the go to seed is easier than removing older ones and reduces future weed populations.</p>
									
									<p>Slugs and snails are a constant problem. Handpicking or beer traps are easy control methods. Another simple trap is to elevate a piece of wood a few inches off the ground in a damp shady area. The slugs and snails will congregate there can be easily gathered and then thrown in the garbage. Use chemical baits only when other treatments fail and be careful so children, pets, and other wildlife do not eat any treatments. Contrary to popular belief, smashing slugs and snails does not spread their eggs.</p>
									
									<p>Many perennials and some annuals will now be finished blooming and are now producing seeds. Many perennials will rebloom if the old flowers and developing seeds are removed, a process called dead heading. The old or spent blossoms should be cut off where the flower stem connects to the leaves usually several inches down in the plant. Since dead-heading also removes unsightly, dry flower heads it also improves the appearance of your garden.</p>
									
									<p>A few perennials like catmint (Nepeta), golden alyssum, and candytuft need extreme dead heading in the form of shearing to about 6 inches to encourage a late summer rebloom. A good reference for perennial care is The Well Tended Perennial Garden by Tracy DiSabato-Aust.</p>
									
									<p>Grass clippings are green gold! Don’t throw them away. When mowing turf-grasses (lawns), use a mulching mower which chops the clippings smaller and leaves them on the lawn. This recycles nutrients back into the turf. You can also use grass clippings as mulch around vegetables, shrubs, and perennials. Clippings are also a great addition to your compost pile. Just keep it stirred to allow the fungi to get some air.</p>
									
									<p>A common garden and lawn weed, black medic, is peaking this time of year. The leaves look similar to clover but with small yellow flowers and grows very close to the ground. When soils are damp, the tap root is easily pulled up by hand. A favorite weeding tool to discourage persistent weeds is a dandelion digger. Check out our gift shop for a wide variety of helpful tools.</p>
									
									<p>Provide an even supply of water to tomatoes to help prevent blossom end rot. Blossom end rot is a symptom of calcium deficiency. It isn’t because there isn’t enough calcium, but that there wasn’t enough water to carry it to the tomato on a regular basis. Routine watering is the best treatment.</p>
									
									<p>Spring flowerings shrubs are now finished and ready to be pruned. These include lilacs, forsythia and spireas. Shrubs benefit the most from “thinning”. This is done by removing several large branches bycutting at the base as close the ground as possible. Three to four large branches is usually sufficient each year. To learn more, our bookstore has several “pruning classics” for sale to give you instruction.</p>
									
									<br />
									
									<hr width="50%" style="background-color:#196143;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />

				<div class="col-sm-6">
					<!-- August Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#aug-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">AUGUST</p>
					        </div>
						</div>
					  </a>
					  <div id="aug-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#196143;" />
							    	
							    	<br />
					    
									<p>Keeping gardens and containers watered this time of year becomes a daily challenge. Watering early in the day or in late evening will help the water soak into the soil instead of evaporating. Do not water between the hours of 10:00 am and 6:00 pm.</p>
									
									<p>Continue to monitor automated sprinkler systems ensuring they are spraying in the right direction and haven’t gotten clogged. As plants grow taller, they can block the water keeping it from spraying out. Trim theses plants or add a temporary sprinkler extension. When temperatures cool, consider moving these taller plants away from spray heads.</p>
									
									<p>Many perennials and some annuals will now be finished blooming and are now producing seeds. Many perennials will rebloom if the old flowers and developing seeds are removed, a process called dead heading. The old or spent blossoms should be cut off where the flower stem connects to the leaves usually several inches down in the plant. Since dead-heading also removes unsightly, dry flower heads it also improves the appearance of your garden.</p>
									
									<p>Annual geraniums (Pelargonium) in particular need to be deadheaded at this time. They can be removed by following the stalk from the old flowers down to where it joins the stem and breaking it off at this point. They easily snap off by hand.</p>
									
									<p>Letting your lawn grow a little taller to 3-4” will help shade the roots and cool the soil. This helps to keep it greener and healthier reducing water need and stress. Raise your mower deck to mow at that height.</p>
									
									<p>Incorrectly called morning glory, field bind weed is a very pernicious weed. Morning glory is a beautiful annual vine that opens up in the evenings. Field bind weed is a perennial that peaks this time of year. It will begin to spread even more dramatically and flower profusely. This is when it is most susceptible to chemical applications from the organic vinegars and lemon juice products to glyphosate and brush removers. All of these act on photosynthesis not in the soil and must be applied to leaves and stems to work. Spraying, waiting a week, and then pulling as much as you can by hand before it completely intertwines with your other plants is imperative. When field bindweed is in lawn areas a broadleaf or dandelion killer will need to be used.</p>
									
									<p>Take a leisurely stroll through your garden looking for areas that need more color. Visit Red Butte Garden and local nurseries to learn more about plants that bloom late in the season. Many reliable perennials like Whirling Butterflies, Coneflowers, hibiscus, and bluebeard begin blossoming now and continue until fall.</p>
									
									<p>Soil tests can provide a lot of answers and guidance in helping you choose plants, fertilizers, and how long to water. The results provide particle size information helping you learn about your drainage and water holding levels. Current nutritional levels and recommendations are also included. For a small fee our local extension service offers this service through out the state. (Utah State Extension Service)</p>
									
									<br />
									
									<hr width="50%" style="background-color:#196143;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>
			
			<br />

			<div class="row">

				<div class="col-sm-6">	
					<!-- September Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#sep-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">SEPTEMBER</p>
					        </div>
						</div>
					  </a>
					  <div id="sep-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#B7330E;" />
							    	
							    	<br />
					    
									<p>Finally some cool evening temperatures begin to trigger fruit to ripen, foliage to turn, flowers to re-bloom, and gardeners to get back in their gardens.</p>
									
									<p>You can encourage blossoms by continuing to dead head (See July for more info).</p>
									
									<p>Flowers have used up much of the nutrition in the soil and are ready to soak up anything you can give them. Geranium’ s and petunias in particular perk up after the heat by applying a tablespoon of Epsom salts sprinkled on top of the soil. Also much of the nitrogen that provides green coloring has been washed out of the soil with extra irrigation. Many trees and shrubs in particular need extra nitrogen and iron. Common deficiency symptoms are yellow leaves with dark veins. Apply a general purpose mix of quick release and slow release fertilizers either organic or synthetic. Liquid feeds that are sprayed directly on foliage can also help.</p>
									
									<p>A great time to plant, roots continue to grow throughout the fall and early winter. This allows them to have an extensive root system before next seasons hot temperatures. This is a great time to go shopping for trees, shrubs and perennials. You can see what is still in bloom and has colorful fall leaves.</p>
									
									<p>Check the root balls of recently purchased plants. If the roots are growing in a circular pattern following the outline of the pot, they are root bound. The roots should be cut and opened up to allow them to grow in new directions out into the surrounding soil. Make an “X” shaped cut on the bottom of the root ball about an inch deep with a cut about halfway up each of the four sides.</p>
									
									<p>A great time to redesign and move plants around, transplant deciduous shrubs and trees when they start to develop fall color. Perennials can be divided and transplanted. Older ornamental grasses can be revived by occasionally uprooting, dividing, and replanting. Division is done by uprooting the entire root ball with as much of it intact as possible. Place the root ball on a hard surface. Usually the center of the perennial or grass is dead resulting in a doughnut like plant. Look for natural splits in the ‘doughnut’ and begin teasing the roots apart into approximately six inch round hunks. If the roots are quite entangled, you can cut them apart into the new sections. Now you can replant or have extra plants to share. Shasta daisies, daylily’s, green fountain grass, and salvia all respond well to division every three to five years.</p>
									
									<p>Order or buy spring bulbs and plant before the ground freezes. A general rule is to plant them twice as deep as the bulb is wide. Join us for a great selection of bulbs at our Fall Plant Sale. Garlic and shallots cloves should be planted several inches deep.</p>
									
									<p>* Stop deadheading roses letting colorful red rose hips form. Let other flowers go to seed producing colorful seed pods and winter browse for birds.</p>
									
									<p>* If your lawn has thick thatch (dead layer) or is compacted from heavy use or wet shade a fall core aeration can loosen and open up the soil. This will help water, nutrition, and air get into the root zone. This is also a wonderful time to reseed lawn areas that are thin or bare. Most lawns are Kentucky bluegrass varieties. More water-wise and heat tolerant dwarf tall fescues are a good choice for over seeding.</p>
									
									<p>*Check your sprinkler system and shorten the watering times of your lawn.</p>
									
									<p>Your hard work is ready to pay off as you harvest and dry your herbs. Harvest them early in the day by cutting off entire stems. Wash everything well and place on screens, cookie sheets or trays and let them air dry for several days. When they are dry, strip the leaves off and store in air tight containers.</p>
									
									<p>Apply a broadleaf weed killer on your lawn. Dandelions are perennial weeds that live from year to year. As the weather cools they begin to store food in their large tap root. They begin pulling nutritional resources from the leaves into the root, thus any chemical applied to the leaves will translocate into the roots. This provides a more complete kill than spring applications.</p>
									
									<p>A second growing season of cool season vegetables is a great way to enjoy your fall. Lettuce, peas, radish, spinach, kale, and chard all perform well in this weather. You can begin to harvest onions, shallots and garlic for use and storage.</p>
									
									<p>Want to learn about native plants for water conservation, perennial and herb care, or how to use stone in the landscape? Check out our monthly calendars for useful classes!</p>
									
									<br />
									
									<hr width="50%" style="background-color:#B7330E;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />
				
				<div class="col-sm-6">
					<!-- October Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#oct-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">OCTOBER</p>
					        </div>
						</div>
					  </a>
					  <div id="oct-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#B7330E;" />
							    	
							    	<br />
					    
									<p>You will wake up to several days of frost by the end of the October. Protect tender garden plants and fruit from light freezes by covering them with blankets, sheets, plastic, or cardboard. Several commercial frost cloths are also available. You just need to keep the moisture off the leaves and the temperature just a couple of degrees warmer. Before a hard frost, when night temperatures will stay at freezing for several hours, harvest tender plants and fruits. Fried green tomatoes can be an especially nice late fall treat; pick, wash, slice, dip in whipped egg, dip in corn meal, and fry in your favorite oil for 1-2 minutes.</p>
									
									<p>For more hardy plants like root crops, you can leave them in the ground until you are ready to use them. Root crops include carrots, turnips, potatoes, beets, winter radishes, and parsnips. If you remove the greenery and cover them with straw, mulch, or soil you can store them in the ground for another month. For more information on extended in ground storage see the <a href="http://www.ext.colostate.edu/pubs/garden/07601.html">Colorado Extension Service Factsheet.</a></p>
									
									<p>Save yourself some spring clean up by removing dead plant debris from annual and vegetable beds after a hard freeze. In areas where tree and shrub roots won’t be damaged, recently frozen vegetation, leaves, and compost can be roto-tilled into the soil.</p>
									
									<p>This is a great time to plant cool season annuals like pansies and primrose. Warm soils keep the roots growing and cool air keeps them blooming. Hand water in generous amounts after planting and during extended dry periods until established.</p>
									
									<p>Sow seeds of self sowing annuals like poppies and cosmos.</p>
									
									<p>Continue planting bulbs such as tulips, daffodils, crocus and others until the ground freezes, usually in November. A general rule of thumb is to plant the bulb two to three times as deep as the widest part of the bulb. If the tulip is 1.5 inches wide, then it should be planted 3 to 4.5 inches deep. Restrain from fertilizing except with bulb food as bulbs are very sensitive to salt damage. Bulb foods have a different chemistry and lower amounts of nutrition that are specifically formulated for bulbs.</p>
									
									<p>A good design tip that also saves some digging is to plant bulbs in clusters or groups. Try placing 8-10 bulbs in a 1 foot wide hole about 1 inch apart from each other. This concentrates the blooms giving you a stronger display of color. Late blooming daffodils can be planted with early blooming varieties to extend the bloom time. This is done by planting 6-8 bulbs of the late variety as listed above, then placing the early variety of bulbs in between and finally back filling.</p>
									
									<p>Wrap the trunks of newly planted and young trees to protect them from winter "sun scald" and from damage by mice, rabbits, and other animals. For larger pests, corrugated plastic drainpipe that has been split lengthwise down the side works well. For sun scald and smaller pests, white cloth about 4 inches wide wrapped around the first 1-2 feet of the trunk works well. Secure the wrapped ends with several lengths of tape. Sun scald happens commonly on thin barked trees like fruiting cherries and young maple trees.</p>
									
									<p>Because plants are going dormant, this is a great time to transplant or move deciduous trees and shrubs. Dormancy is shown by the change in leaf color and dropping of leaves. Keeping the root ball intact as much as possible will aid the success of the move. To help with this, try not to have the soil extremely wet, but mildly damp. Handling the tree by the root ball and not the trunk will also help the keep the root ball together. After transplanting, apply water slowly to the root ball for the next several days to ensure the newly exposed roots can access water and keep the tree turgid.</p>
									
									<p>Continue to add to your compost pile with garden waste; leaves, grass clippings, and other vegetative materials. Remember a happy compost pile has air and moisture, so stir it and water it. Try not to add weeds that have gone to seed, diseased clippings, or any kitchen waste containing meat products.</p>
									
									<p>Deep-water evergreens to prepare them for winter.</p>
									
									<p>Move tender perennials and other potted plants into protected or heated enclosures prior to a killing frost. This includes tender pond plants like locusts, papyrus, and some water lilies. Make sure to thoroughly spray down leaves to remove as many insects as possible. Trim off dead and older leaves that may become a source of disease.</p>
									
									<p>Open sprinkler valves and drain water from sprinkler systems to prevent freezing. This is done by first turning off your main water source that supplies the sprinkler system. Then open each valve for several minutes to release any water or air pressure in the line. If your pipes are installed less than 12 inches deep in the ground without drain valves, it may be best to use an air compressor to blow remaining water out of the lines.</p>
									
									<p>Dig the hole and prepare the site for the future planting of your live Christmas tree.</p> 
									
									<br />
									
									<hr width="50%" style="background-color:#B7330E;" />
									
								</div>
								
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>

			<br />
			
			<div class="row">

				<div class="col-sm-6">	
					<!-- November Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#nov-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">NOVEMBER</p>
					        </div>
						</div>
					  </a>
					  <div id="nov-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
							<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#B7330E;" />
							    	
							    	<br />
					    
									<p>Plant tulips, daffodils, crocus, and other bulbs. Add complete fertilizer or "Bulb Booster" at the bottom of the hole and mix it with the soil before planting the bulbs.. If you want to dig fewer holes, "layer" bulbs. Plant the bigger bulbs at the proper depth, add soil, and plant smaller bulbs on top of them, again, at the proper depth.</p>
									
									<p>Plant a few bulbs in pots for forcing. Paperwhites, hyacinths, and early blooming tulips and daffodils are good choices.</p>
									
									<p>Empty and sterilize, with a mixture of 1:9 parts bleach and water, terra cotta and ceramic pots and store in a protected area, such as garage, shed, or basement to prevent cracking</p>
									
									<p>Open sprinkler valves and drain water from sprinkler systems to prevent freezing.</p>
									
									<p>Drain and store hoses.</p>
									
									<p>Collect dried seedpods, grass stalks, seedheads, and other dried plant materials for use in making flower or plant arrangements.</p>
									
									<p>Buy birdseed and fill bird feeders. Consider buying a heater for your birdbath; Water is often times more important than food during winter.</p>
									
									<p>Wrap tall arborvitae, junipers, yews, and other evergreen shrubs with burlap or twine to prevent snow damage and breakage. If deer say, "thank you for planting this:", wrapping bird netting around the plant will often help save it.</p>
									
									<p>Wrap the trunks of young, thin-barked trees with paper tree wrap late in the month to prevent sunscald.</p>
									
									<p>Clean, repair, and properly store tools and garden implements so they will be ready for use in the spring. Apply a thin coat of oil on steel implements to protect them from rust.</p>
									
									<p>Drain gas from lawnmowers, weed-eater, edgers, and other gas powered equipment prior to storage.</p>
									
									<p>Start a compost pile with fall garden debris.</p>
									
									<p>After all the leaves have fallen from a diseased plant, pick up the leaves AND mulch from around it. If left on the ground, disease spores will live in the debris over the winter and will resurface next year.</p>
									
									<p>Turn vegetable garden soil. Turning soil exposes many insect pests to winter cold, reducing their numbers in next year's garden. Consider planting a "green manure" crop, such as winter rye, to help improve the organic matter in your soil.</p>
									
									<p>Remember to water any newly-planted trees and shrubs until the ground freezes. Evergreens continue to lose moisture from their leaves or needles all winter long. Without adequate water in the ground before a hard freeze, extra stress is put on evergreens through the winter. Whenever the temperature is above freezing, water your evergreens.</p>
									
									<p>Add mulch (up to three inches, total) around trees, shrubs, and perennials AFTER the ground is frozen. Adding mulch after the ground freezes keeps the temperature from fluctuating, helping to prevent heaving.</p>
									
									<br />
									
									<hr width="50%" style="background-color:#B7330E;" />
									
								</div>
								
							</div>
							
						</div>
					  </div>
					</div>
				</div>

				<br class="br-hide-lg" />
				
				<div class="col-sm-6">
					<!-- December Start -->
					<div class="panel panel-default no-border">
					  <a data-toggle="collapse" data-parent="#gardeningaccordion" href="#dec-tips">
					  	<div class="panel-heading garden-panel no-border hover" style="background-color:#196143;">
					        <div class="panel-title">
					        	<p class="text-center white">DECEMBER</p>
					        </div>
						</div>
					  </a>
					  <div id="dec-tips" class="panel-collapse collapse">
					    <div class="panel-body">
					    
					    	<div class="row-fluid">
						    	
								<div class="col-sm-12">
								
									<hr width="50%" style="background-color:#158FBF;" />
							    	
							    	<br />
					    
									<p><strong>December Garden Tips:</strong></p>
									
									<p>Continue to water evergreen plants until ground freezes to prevent winter sun-scald.</p>
									
									<p>Provide a water source for thirsty birds throughout the winter by installing a heater in your birdbath. Or change out the water when it freezes.</p>
									
									<p>Fill birdfeeders throughout winter months. Suet is a great source of protein.</p>
									
									<p>Wrap tall arborvitae, junipers, yews, and other evergreen shrubs with burlap or twine to prevent snow damage and breakage.</p>
									
									<p>Start paperwhite bulbs in gravel, marbles or soil every other week for flowers throughout the winter months</p>
									
									<p>Plant amaryllis bulbs now for January bloom.</p>
									
									<p>Check house plants for insects. Examine them carefully by looking under leaves and in leaf axils. Early detection makes control much easier. Simple pruning or washing with mild dish-soap and water may remedy problem (add a couple drops of dish-soap to a spray bottle full of lukewarm water).</p>
									
									<p><strong>Tips for buying a fresh-cut Christmas tree and how to care for it:</strong></p>
									
									<p>Choose a fresh tree. A fresh tree will have a healthy green appearance with few browning needles. Needles should be flexible and not fall off if you run a branch through your hand. When a tree becomes dry it is time to take it out of the house.</p>
									
									<p>Locate the tree at least three feet away from any kind of heat source, like fireplaces, heat vents and even candles to prevent a house fire.</p>
									
									<p>Check the water level daily and be sure to keep it well above the base of the tree. If the base dries out, resin will form over the cut end and the tree will not be able to absorb water.</p>
									
									<p>Make a fresh green wreath with the boughs removed from the bottom of your tree.</p>
									
									<p><strong>Tips for buying a live Christmas tree and how to care for it:</strong></p>
									
									<p>Identify where your live tree will be planted in the yard after Christmas and dig the hole before the ground freezes.</p>
									
									<p>Before bringing the tree inside it should be conditioned by putting in an unheated garage for a few days. The same should be done when moving it back outside to be planted.</p>
									
									<p>Live trees are fairly sensitive and should not be kept inside for more than 10 days.</p>
									
									<p>Prior to moving the tree inside, the root ball should be moistened and kept in a moist condition while the tree is displayed. The root ball should be placed in a bucket or a large pan to prevent soil and water from staining the floor. The rootball should remain moist but not stand in water.</p>
									
									<p>Make sure to locate living trees away from heat sources. Living Christmas trees will also need water, although not nearly as much as cut trees.</p>
									
									<p>Check out this link to the National Christmas Tree Association for more:<br />
									<a href="http://www.realchristmastrees.org/dnn/AllAboutTrees/CareTips.aspx">http://www.realchristmastrees.org/dnn/AllAboutTrees/CareTips.aspx</a></p>
									
									<br />
									
									<hr width="50%" style="background-color:#158FBF;" />
									
								</div>
									
					    	</div>
							
						</div>
					  </div>
					</div>
				</div>
			</div>
			
		</div>
			
			<br />

		</div>
					
	</div>
<!-- END MONTHLY GARDENING TIPS PANEL -->

</div>

<br class="br-hide" />

<div class="row">

<!-- BEGIN PLANT PROFILES PANEL -->
	
	<div class="col-sm-6">
		
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#waterwise-articles" data-toggle="collapse">WATER-WISE ARTICLES</button>
		</span>
		
		<div class="collapse panel-border" id="waterwise-articles">
			
			<br />

			<h3 class="green text-center">Water-Wise Articles</h3>
				
			<div class="row-fluid">
			
				<div class="col-xs-12">
				
				<p>Red Butte Garden is maintained by skilled and talented horticulture experts who embrace the challenges associated with gardening in Utah. Following is a list of articles to help you understand water conservation, best practices, and just how interesting and fun it can be to create your own water conservation garden.</p>
	
				<ul>
					<li><a href="/word-wise-about-water-wise">Word Wise About Water-Wise</a></li>
					<li><a href="/saving-water">Saving Water in the Garden</a></li>
					<li><a href="/plant-adaptations-to-arid-environments">Plant Adaptations to Arid Environments</a></li>
				</ul>
				
				<p><a href="http://attheu.utah.edu/wp-content/uploads/2015/09/16-0053-Landscaping-Water-Infographic.jpg"><em>Curious about the proper use of landscaping terms? Click here!</em></a></p>
	
				</div>
				
			</div>
			
		</div>

	</div>

	<div class="col-sm-6">
		
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#plant-profiles" data-toggle="collapse">PLANT PROFILES</button>
		</span>
		
		<div class="collapse panel-border" id="plant-profiles">
			
			<br />
			
			<h3 class="green text-center">Plant Profiles</h3>
			
			<div class="row-fluid">
			
				<div class="col-xs-12">
										
					<ul>
					
						<li><a href="/documents/agastache.pdf">Agastache <em class="normal">Agastache cvs</em></a></li>
						<li><a href="/documents/alpine-violet.pdf">Alpine Violet <em class="normal">Cyclamen coum</em></a></li>
						<li><a href="/documents/american-sweetgum.pdf">American Sweetgum <em class="normal">Liquidambar styraciflua</em></a></li>
						<li><a href="/documents/arizona-blue-cypress.pdf">Arizona Blue Cypress <em class="normal">Cupressus arizonica</em> 'Blue Pyramid'</a></li>
						<li><a href="/documents/banana-yucca.pdf">Banana Yucca <em class="normal">Yucca baccata</em></a></li>
						<li><a href="/documents/blackgum.pdf">Blackgum <em class="normal">Nyssa sylvatica</em></a></li>
						<li><a href="/documents/blue-star-flower.pdf">Blue Star Flower <em class="normal">Amsonia tabernaemontana</em></a></li>
						<li><a href="/documents/bosnian-pine.pdf">Bosnian Pine <em class="normal">Pinus leucodermis</em></a></li>
						<li><a href="/documents/bristlecone-pine.pdf">Bristlecone pine <em class="normal">Pinus aristata</em></a></li>
						<li><a href="/documents/bugle-weed.pdf">Bugle Weed <em class="normal">Ajuga reptans</em></a></li>
						<li><a href="/documents/butterfly-bush.pdf">Butterfly Bush <em class="normal">Buddleja davidii</em></a></li>
						<li><a href="/documents/chocolate-vine.pdf">Chocolate Vine <em class="normal">Akebia quinata</em></a></li>
						<li><a href="/documents/cream-puff-cedar.pdf">Cream Puff Cedar <em class="normal">Cedrus deodara 'Cream Puff'</em></a></li>
						<li><a href="/documents/crocus-sativus.pdf">Crocus sativus <em class="normal">Crocus sativus</em></a></li>
						<li><a href="/documents/curl-leaf-mountain-mahogany.pdf">Curl-Leaf Mountain Mahogany <em class="normal">Cercocarpus ledifolius</em></a></li>
						<li><a href="https://docs.google.com/presentation/d/1DJNYIMs-LImzVFwF0JuoflhkzZamVjVN6VswH01mg3w/edit#slide=id.p">Daffodils <em class="normal">Narcissus Cultivars</em> <span class="red">MISSING</span></a></li>
						<li><a href="/documents/dragons-eye-pine.pdf">Dragon's Eye Pine <em class="normal">Pinus densiflora</em> 'Oculus Draconis'</a></li>
						<li><a href="/documents/.pdf">Dwarf Bear-Claw Poppy <em class="normal">Arctomecon humilis</em> <span class="red">MISSING</span></a></li>
						<li><a href="/documents/elderberry.pdf">Elderberry <em class="normal">Sambucus</em></a></li>
						<li><a href="/documents/firetail-fleeceflower.pdf">Firetail Fleeceflower <em class="normal">Persicaria amplexicaulis</em> 'Firetail'</a></li>
						<li><a href="/documents/fourwing-saltbush.pdf">Fourwing Saltbush <em class="normal">Atriplex canescens</em></a></li>
						<li><a href="/documents/gaura.pdf">Gaura <em class="normal">Gaura lindheimeri</em> 'Whirling Butterflies'</a></li>
						<li><a href="/documents/giant-sequoia.pdf">Giant Sequoia <em class="normal">Sequoiadendron giganteum</em></a></li>
						<li><a href="/documents/gibraltar-bush-clover.pdf">Gibraltar Bush Clover <em class="normal">Lespedezia thunbergii</em> 'Gibraltar'</a></li>
						<li><a href="/documents/.pdf">Graham's Penstemon Penstemon grahamii</em> <span class="red">MISSING</span></a></li>
						<li><a href="/documents/horstmanns-silberlocke-korean-fir.pdf">Horstmann's Silberlocke Korean Fir <em class="normal">Abies koreana</em> 'Horstmann's Silberlock'</a></li>
						<li><a href="/documents/kentucky-coffee-tree.pdf">Kentucky Coffee Tree <em class="normal">Gymnocladus dioicus</em></a></li>
						<li><a href="/documents/lacebark-pine.pdf">Lacebark Pine <em class="normal">Pinus bungeana</em></a></li>
						<li><a href="/documents/liverwort.pdf">Liverwort Hepatica <em class="normal">nobilis</em></a></li>
						<li><a href="/documents/meadow-saffron.pdf">Meadow Saffron <em class="normal">Colchicum autumnale</em></a></li>
						<li><a href="/documents/northern-sea-oats.pdf">Northern Sea Oats <em class="normal">Chasmanthium latifolium</em></a></li>
						<li><a href="/documents/oakleaf-sumac.pdf">Oakleaf Sumac <em class="normal">Rhus aromatica var. trilobata</em></a></li>
						<li><a href="/documents/paperbark-maple.pdf">Paperbark Maple <em class="normal">Acer griseum</em></a></li>
						<li><a href="/documents/parrys-agave.pdf">Parry's Agave <em class="normal">Agave parryi</em></a></li>
						<li><a href="/documents/pest-resistant-bulbs.pdf">Pest Resistant Bulbs</em></a></li>
						<li><a href="/documents/prince-aster.pdf">Prince Aster <em class="normal">Aster lateriflorus</em> 'Prince'</a></li>
						<li><a href="/documents/pinon-pine.pdf">Piñon Pine <em class="normal">Pinus edulis</em></a></li>
						<li><a href="/documents/prairie-dropseed.pdf">Prairie Dropseed <em class="normal">Sporobolus heterolepis</em></a></li>
						<li><a href="/documents/rugosa-rose.pdf">Rugosa Rose <em class="normal">Rosa Rugosa</em></a></li>
						<li><a href="/documents/savory.pdf">Savory <em class="normal">Satureja spp.</em></a></li>
						<li><a href="/documents/screwpine.pdf">Screwpine <em class="normal">Pandanus utilis</em></a></li>
						<li><a href="/documents/sego-lily.pdf">Sego Lily <em class="normal">Calochortus nuttallii</em></a></li>
						<li><a href="/documents/seven-son-flower.pdf">Seven Son Flower <em class="normal">Heptacodium miconioides</em></a></li>
						<li><a href="/documents/shenandoah-switch-grass.pdf">Shenandoah Switch Grass <em class="normal">Panicum virgatum</em> 'Shenandoah'</a></li>
						<li><a href="/documents/skunkbush-sumac.pdf">Skunkbush Sumac <em class="normal">Rhus aromatica var. aromatica</em></a></li>
						<li><a href="/documents/swamp-hibiscus.pdf">Swamp Hibiscus <em class="normal">Hibiscus coccineus</em></a></li> 
						<li><a href="/documents/sweet-woodruff.pdf">Sweet Woodruff <em class="normal">Gallium odoratum</em></a></li> 
						<li><a href="/documents/the-indestructible-rose.pdf">The Indestructible Rose Species Roses</a></li>
						<li><a href="/documents/utah-penstemon.pdf">Utah Penstemon <em class="normal">Penstemon utahensis</em></a></li>
						<li><a href="/documents/viburnum.pdf">Viburnum <em class="normal">Viburnum sp</em></a></li>
						<li><a href="/documents/vitex-chase-tree.pdf">Vitex Chase Tree Vitex sp</em></a></li>
						<li><a href="/documents/weeping-blue-atlast-cedar.pdf">Weeping Blue Atlast Cedar <em class="normal">Cedrus atlantica</em> 'Glauca Pendula'</a></li>
						<li><a href="/documents/western-river-birch.pdf">Western River Birch <em class="normal">Betula occidentalis</em></a></li>
						<li><a href="/documents/wild-hollyhocks.pdf">Wild Hollyhocks <em class="normal">Iliamna rivularis</em></a></li>
						<li><a href="/documents/wild-strawberry.pdf">Wild Strawberry <em class="normal">Fragaria vesca</em></a></li>
						<li><a href="/documents/winter-flame-dogwood.pdf">Winter Flame Dogwood <em class="normal">Cornus sanguinea</em> 'Winter Flame'</a></li>
						<li><a href="/documents/wintersweet.pdf">Wintersweet <em class="normal">Chimonanthus praecox</em></a></li>
						<li><a href="/documents/yellowhorn.pdf">Yellowhorn <em class="normal">Xanthoceras sorbifolium</em> 'Psgan'</a></li>
				
					</ul>
								
				</div>
				
			</div>
			
			<br />
		
		</div>
			
	</div>

</div>
<!-- END PLANT PROFILES PANEL -->

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