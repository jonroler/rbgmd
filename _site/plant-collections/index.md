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
<title>Plant Collections</title>
    

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
	<img src="/images/banners/plant-collections.jpg" class="responsive" alt="Plant Collections at Red Butte Garden" title="Plant Collections at Red Butte Garden" />
</div>

<br />

<div class="row-fluid">

	<div class="col-xs-12">
		
		<br />
		
		<p>Red Butte Garden is a museum of living plants. Plants are collected for their horticultural merit, use in research and conservation, and for their historical value. Each plant is given an accession number and carefully curated within the collections. To learn about our collections and displays, please click on the corresponding images below.</p>	
		
		<!-- Panel with more information about our Plant Collections -->
		<div class="panel-group" id="accordion">
	
		    <div class="panel panel-default">
		      <a data-toggle="collapse" data-parent="#accordion" href="#PC">
		      	<div class="panel-heading">
			        <div class="panel-title"><center>Click Here for More Info on our Types of Plant Collections</center></div>
				</div>
		      </a>
		      <div id="PC" class="panel-collapse collapse">
		        <div class="panel-body">
		        	
		        	<p>Red Butte Garden has several types of plant collections and each accession falls into one or more of the following categories:
			
						<ul>
							<li><strong>Arboretum:</strong> A collection of trees, held jointly on the University of Utah campus and Red Butte Garden.</li>
							<li><strong>Ecological:</strong> Plants native to Utah.</li>
							<li><strong>Ethnobotanic:</strong> Plants that have a history of use by humans.</li>
							<li><strong>Geographic:</strong> Plants with horticultural value from other states or countries that perform well in our climate.</li>
							<li><strong>Research/Conservation:</strong> Threatened, rare, and endangered species.</li>
							<li><strong>Taxonomic:</strong> Represents species, varieties, and cultivars of select taxa.</li>
						</ul>
					
		        	</p>
		        	
		        	<p>Aside from our impressive collections, we also maintain a variety of ornamental displays. Displays are plants that are not included in our curated plant collections. We do not keep the same records on them. Rather, they are used to enhance our landscape plantings. Our most noteworthy displays include: <strong>Daffodils</strong>, <strong>Miniature Bulbs</strong>, and <strong>Succulents</strong>.</p>
					
				</div>
		      </div>
		    </div>
		
		</div>

	</div>

</div>

<hr width="95%">

<div class="row-fluid">

	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1C7aOrPWwWUlW3C9uiyvy6PnaX_PltyaC33btRvc-1us/edit#slide=id.g18adb1019d_0_207" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/conifer.jpg">
			
			<div class="eventinfo">
				<div class="eventname">CONIFER COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap">
			<h4 class="green">Conifer Collection</h4>
			
			<p>Conifers are woody plants that bear cones. They range in size from the tallest tree in the world (Sequoia sempervirens or Coast Redwood) to small dwarf varieties. Conifers are also among the oldest known trees, with Methuselah, a Bristlecone Pine from California, estimated to be around 5,000 years old. Most conifers are recognized by their needle-like foliage and are often described as evergreens, however, some varieties such as Larches and Bald Cypress, are deciduous, losing their leaves in the fall.</p>
			
			<p>At Red Butte Garden, the purpose of our Conifer Collection is to display a wide variety of conifer and other gymnosperm taxa emphasizing the diversity of size, form, color, and texture and to showcase the assortment of conifers available for use in the home landscape.</p>
		
			<p>As we continue to expand and diversify our collection, we seek to increase the diversity of Utah native species, water-wise species, unusual or rare forms, and miniature and dwarf varieties.</p>
			
			<p><a href="https://docs.google.com/presentation/d/1C7aOrPWwWUlW3C9uiyvy6PnaX_PltyaC33btRvc-1us/edit#slide=id.g18adb1019d_0_207" target="_blank">Click here to view our Conifer Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">

<div class="row-fluid">

	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1nbNsyaCvd-rn5fOX18ABFm3-w3L4NZKeNGJr4d3Ug60/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/ornamental-grass.jpg">
			
			<div class="eventinfo">
				<div class="eventname">ORNAMENTAL GRASS COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Ornamental Grass Collection</h4>
			
			<p>At Red Butte Garden, the purpose of our Ornamental Grass Collection is to display a wide variety of non-invasive ornamental grasses and grass-like plants, emphasizing the diversity of taxa, size, form, color, and texture.</p>
			
			<p>As we continue to expand and diversify our collection, we seek to increase the diversity of genera, species, varieties, and cultivars that demonstrate the variety or ornamental grasses available for the home landscape and how they perform in our region.</p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1nbNsyaCvd-rn5fOX18ABFm3-w3L4NZKeNGJr4d3Ug60/edit?usp=sharing" target="_blank">Click here to view our Ornamental Grass Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">

<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1wgvZur9cRmmpHJwq2coz9zpt_hhizahijKn9Z8io54c/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/rose.jpg">
			
			<div class="eventinfo">
				<div class="eventname">ROSE COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Rose Collection</h4>
			
			<p>Roses are among the most loved flowers in the world. There are about 150 distinct species, all found only in the northern hemisphere. Modern rose varieties began to appear in the late 18th century when repeat-blooming roses from China were introduced to Europe. Today, there are a wealth of roses available from which to choose, from hybrid teas and floribundas to shrub roses and groundcovers, from climbers and ramblers to miniatures. Old roses and species roses also add their beauty and charm to gardens.</p>
			
			<p>At Red Butte Garden, the purpose of our Rose Collection is to display a wide variety of roses emphasizing a diversity of ornamental characteristics such as: flower color, form and fragrance; fall/winter interest, plant size, form and texture.</p>
		
			<p>As our Collection grows, we strive to obtain species and cultivars of all rose classes that are winter-hardy and with an emphasis on disease resistant to showcase the variety of roses that thrive in Utah.</p>
			
			<p><a href="https://docs.google.com/presentation/d/1wgvZur9cRmmpHJwq2coz9zpt_hhizahijKn9Z8io54c/edit?usp=sharing" target="_blank">Click here to view our Rose Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">

<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1DJNYIMs-LImzVFwF0JuoflhkzZamVjVN6VswH01mg3w/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/daffodil.jpg">
			
			<div class="eventinfo">
				<div class="eventname">DAFFODIL DISPLAY</div>
			</div>
	
		</div>
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Daffodil Display</h4>
			
			<p> Red Butte Garden presents a stunning display each spring of over 450,000 bulbs (to date), 230,000 of which are daffodils. Daffodils were chosen as a prominent component due to their long lifespan, wide diversity of color, size and bloom type, and dislike by wildlife such as deer and squirrels.</p>
			
			<p> The Red Butte Garden daffodil display started in 2003 in the Four Seasons Garden. The Four Seasons Garden, situated on a hill facing the Visitor Center, is the first thing that visitors see when they enter the Garden. This garden space, composed of large masses of plants best appreciated when viewed from a distance, lends itself well to a massive display of daffodils, with varieties chosen that, due to their size and color, stand out from a distance.</p>
		
			<p>In 2013, Red Butte Garden was recognized as an official Daffodil Display Garden by the American Daffodil Society. The display represents all 13 recognized divisions, which are based on floral parts and species derivation.</p>
			
			<p><a href="https://docs.google.com/presentation/d/1DJNYIMs-LImzVFwF0JuoflhkzZamVjVN6VswH01mg3w/edit?usp=sharing" target="_blank">Click here to view our Daffodil Display</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1zHR2eacGY99f6QLNMQNaL4Wpu_9IQ7CvCYFKUmt17PI/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/penstemon.jpg">
			
			<div class="eventinfo">
				<div class="eventname">PENSTEMON COLLECTION</div>
			</div>
			
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Penstemon Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1zHR2eacGY99f6QLNMQNaL4Wpu_9IQ7CvCYFKUmt17PI/edit?usp=sharing" target="_blank">Click here to view our Penstemon Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/197Ks2R5feWlc5CncF-2CDt_iRKRkJok43SHC9oJG1w0/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/ethnobotanical.jpg">
			
			<div class="eventinfo">
				<div class="eventname">ETHNOBOTANICAL COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Ethnobotanical Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/197Ks2R5feWlc5CncF-2CDt_iRKRkJok43SHC9oJG1w0/edit?usp=sharing" target="_blank">Click here to view our Ethnobotanical Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1bpB3uJ4UUpVDT4ks99ffd5pl6e-U3lCxlIdJEiKJb7I/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/herb.jpg">
			
			<div class="eventinfo">
				<div class="eventname">HERB COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Herb Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1bpB3uJ4UUpVDT4ks99ffd5pl6e-U3lCxlIdJEiKJb7I/edit?usp=sharing" target="_blank">Click here to view our Herb Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1kSl750BaOqDK0Kgm8knptayIK0KGZZ26d3oXLCJ6-Eg/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/crabapple.jpg">
			
			<div class="eventinfo">
				<div class="eventname">CRABAPPLE COLLECTION</div>
			</div>
	
		</div>
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Crabapple Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1kSl750BaOqDK0Kgm8knptayIK0KGZZ26d3oXLCJ6-Eg/edit?usp=sharing" target="_blank">Click here to view our Crabapple Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1jVw0RAhXhqcSHw-bV8LUYkX_q8AxIkOOADJIsrliOjg/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/hybrid-oak.jpg">
			
			<div class="eventinfo">
				<div class="eventname">HYBRID OAK COLLECTION</div>
			</div>
	
		</div>
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Hybrid Oak Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1jVw0RAhXhqcSHw-bV8LUYkX_q8AxIkOOADJIsrliOjg/edit?usp=sharing" target="_blank">Click here to view our Hybrid Oak Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1Woisy26YPfFcwM5PXnw7iBWNR0-nxx3QnjLVPARuqrY/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/utah-native.jpg">
			
			<div class="eventinfo">
				<div class="eventname">UTAH NATIVE COLLECTION</div>
			</div>
	
		</div>
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Utah Native Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1Woisy26YPfFcwM5PXnw7iBWNR0-nxx3QnjLVPARuqrY/edit?usp=sharing" target="_blank">Click here to view our Utah Native Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/11uP7Zn8aGSb-OTkqd1uT7tSX0B6m3VB5Rt9Tk1gfBTs/edit?usp=sharing" target="_blank">
		<div class="collectionswrap hover">
		
			<img src="../images/collections/viburnum.jpg">
			
			<div class="eventinfo">
				<div class="eventname">VIBURNUM COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Viburnum Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/11uP7Zn8aGSb-OTkqd1uT7tSX0B6m3VB5Rt9Tk1gfBTs/edit?usp=sharing" target="_blank">Click here to view our Viburnum Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->

<!--
<div class="row-fluid">
	
	<div class="col-sm-6">
		<a href="https://docs.google.com/presentation/d/1hqDInvlvMb_TnHdGslA9-52wGiyiC1zMIFSzryn4ztM/edit?usp=sharing" target="_blank">
			<div class="collectionswrap hover">
		
			<img src="../images/collections/artemesia.jpg">
			
			<div class="eventinfo">
				<div class="eventname">ARTEMESIA COLLECTION</div>
			</div>
	
		</div>	
		</a>
	</div>
	
	<div class="col-sm-6">
		<div class="collectionswrap green">
			<h4 class="green">Artemesia Collection</h4>
			
			<p></p>
			
			<p></p>
		
			<p></p>
			
			<p><a href="https://docs.google.com/presentation/d/1hqDInvlvMb_TnHdGslA9-52wGiyiC1zMIFSzryn4ztM/edit?usp=sharing" target="_blank">Click here to view our Artemesia Collection</a></p>
		</div>
	</div>
	
</div>
<br />
<hr width="95%">
-->
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