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
<title>Pruning 101</title>
    

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
        <h2 class="green text-center">Pruning 101</h2>
<hr>

<br />

<div class="row-fluid">

	<div class="col-xs-12">
	
<p>As broad as the choices of plants for a landscape are, so too are the options for pruning. How to prune and when can depend on the time of the year, the type of plant, and your personal aesthetics. The following information on perennials, grasses, roses, shrubs, and trees is meant to serve as a practical guide alongside which personal aesthetics will always play a role.</p>

<p>Perennials and ornamental grasses can be cut back in the fall after a hard frost, or in the spring before new growth begins. They should be cut back to a couple inches above the ground level. A pruning handsaw works well when cutting back ornamental grasses. If you enjoy the foliage of grasses and the seedheads of perennials in the winter garden, spring is clearly the better option. Spring pruning should occur in February or early March to assure the new season’s growth is not damaged. Many herbs, such as chives, sorrel, rue, and fennel are also perennials and should be treated as such.</p>

<h4 class="green">Herbs</h4>

<p>Herbs that are partially woody in habit should not be pruned to the ground level each year. Instead, these plants should be pruned in spring after the threat of a hard frost is over. Winter savory makes a great flowering groundcover but is sensitive to a late frost if last year’s seedheads are removed too early. Sage and Lavender can be left unpruned if you prefer a more natural and spreading plant. However if you prefer a tighter look, they both tolerate a heavy pruning. Garden sage (Salvia officinalis) can be pruned back to the woody stems, approximately 6” or so. Lavender can be pruned to remove almost all of last season’s growth; however, limit fall pruning to removing the flower stalks. A hard pruning is sometimes preferred as they can die out in the center with age.
It is important to note that the word ‘perennial’ means the plant will live 3 or more years. Herbaceous perennials, including herbs, will decline and/or die at times and need to be replaced. This should be understood and expected.</p>

<h4 class="green">Shrubs</h4>

<p>When pruning shrubs, or any woody plant, personal aesthetics play a large part. If you prefer the natural habit of shrubs and have room for it to reach its natural size, then prune only diseased, dead, or broken branches. If you prefer a bush that is shaped or kept within certain size restraints, prune back to the desired shape or size after blooming in order to maximize the enjoyment of the blooming period. For some shrubs this is in the fall, for others it is in the late spring.</p>

<p>Shrubs that have a lot of deadwood and need remedial attention may be heavily pruned using one of two methods. Rejuvenation is a method of pruning the entire shrub to the ground, usually within a few inches. Shrubs such as Potentilla, Spiraea, Hypericum and Kerria respond well to this type of pruning. Once rejuvenated, they do not need to be rejuvenated for a several years. The second method, thinning, is a practice that removes a third or fourth of the oldest canes or stems each year over a period of 3 or 4 years. These older stems should be removed as close to the base of the shrub as possible without harming the younger growth. This practice is preferred on shrubs that do not respond well to rejuvenation, such as Lilacs, Viburnums, Amelanchier, Forsythia and Red Twig Dogwoods. Thinning encourages new growth from the plant base and keeps the plant full and fresh with new growth.</p>

<p>Some shrubs such as Buddleia, Perovskia and Caryopteris typically have varying degrees of dieback after the winter season. It is important to be patient with these plants and prune them after you see new foliage emerge. You can then prune them back to just above the emerging foliage.</p>

<h4 class="green">Roses</h4>

<p>How to prune roses depends on the type of roses you’re growing. Roses can be very susceptible to fungus and need pruning to let air movement keep the foliage dry. This is especially true of Hybrid Teas. When pruning hybrid tea roses in the spring, select the best 3 – 5 canes and remove canes that are diseased or will crowd your chosen canes. Prune your selected canes below any winter dieback or disease and to a bud that will grow to the outside of the rose bush. When removing dead flowers, prune to the first leaf with 5 leaflets (on some roses its 7 - 9 leaflets) on a leaf that the bud will grow to the outside of the plant. It is important that new growth will grow to the outside of the plant rather than the inside to allow air movement within the bush and minimize fungus problems. Pruning in the fall should be minimal as roses store food for the winter in their stems.</p>

<p>Climbing roses only need training for your structure and the occasional removal of a diseased branch. The spent blossoms can be removed. However, if it is a variety with showy hips then they should be left alone.
Meidiland and Shrub Roses have less disease problems and do not require regular pruning; in fact they should be left to form their natural shape. Depending on the cultivar, this can be anywhere from 4’ to 6’ and larger. Many shrub roses have showy hips, so spent blossoms should be left. When pruning these easy roses, simply remove the occasional dead or diseased branch.</p>

<p>One final note about roses: many roses, especially hybrid teas, are grafted on wild rootstock, thus explaining the occasional sport of a different growth pattern and flower color. These should be dug down and removed at the root. To avoid this problem all together, purchase roses grown on their own rootstock. Although this may be difficult with hybrid teas, it is entirely possible with shrub roses.</p>

<h4 class="green">Trees</h4>

<p>The best time to prune trees is during the winter or summer. Avoid pruning in the spring when the buds are enlarging and the leaves unfolding because their energy reserves are at their lowest point. The additional stress of pruning at this time can be very harmful. Also avoid the fall when the leaves are coloring. Pruning at this time can cause the plant to produce a flush of growth and may prevent the tree from hardening off in time for winter.
The first thing to do is to remove dead, dying, and decayed branches. Then remove crossing branches, broken branch stubs, branches with included bark (discussed below), watersprouts, and suckers. Then decide what, if any, other pruning is desired. It is important not to remove too much material in a single season. You may need to phase the shaping and training of the tree over a few years.</p>

<p>Included bark is term used to describe a defect in how a branch is attached. Instead of branch wood and trunk wood being properly connected, they are growing next to each other but separate. This condition can be detected on the exterior of the tree by looking at the branch bark ridge. In a properly attached branch, the branch bark ridge flairs outward. If the attachment has bark included, there is a seam that rolls inside at the center of the branch bark ridge. Compare the difference in the two pictures.</p>
	
<br />
	
<div class="row">	
	
	<div class="col-sm-3">
		<a href="/images/misc/pruning-figure-1.jpg"><img src="/images/misc/pruning-figure-1.jpg" class="responsive" alt="Proper Branch Attachment" title="Proper Branch Attachment" /></a>
		<h6 class="text-center"><em>Figure 1: Proper Branch Attachment</em></h6>
	</div>
	
	<div class="col-sm-3">
		<a href="/images/misc/pruning-figure-2.jpg"><img src="/images/misc/pruning-figure-2.jpg" class="responsive" alt="Included Bark" title="Included Bark" /></a>
		<h6 class="text-center"><em>Figure 2: Included Bark</em></h6>
	</div>
	
	<div class="col-sm-3">
		<a href="/images/misc/pruning-figure-2.1.jpg"><img src="/images/misc/pruning-figure-2.1.jpg" class="responsive" alt="Partial Included Bark" title="Partial Included Bark" /></a>
		<h6 class="text-center"><em>Figure 2.1: Partial Included Bark</em></h6>
		<p class="text-center">Prune branches using the natural target method: look for a swelling at the base of the branch as it joins the trunk and cut just outside the swelling. A correctly pruned branch will not be pruned flush with the trunk. Instead, it will start just outside the branch bark ridge and angle out slightly, leaving a slight protrusion from the trunk at the base of the cut branch.</p>
	</div>
	
	<div class="col-sm-3">
		<a href="/images/misc/pruning-figure-3.jpg"><img src="/images/misc/pruning-figure-3.jpg" class="responsive" alt="Proper Pruning Cut" title="Proper Pruning Cut" /></a>
		<h6 class="text-center"><em>Figure 3: Proper Pruning Cut</em></h6>
	</div>

</div>

<br />	
	
<p>When removing large branches, it is important to use a 3-step method. This method removes the weight of the branch so that a proper cut can be made without ripping bark down the trunk. First, make an undercut several inches to a foot from the trunk; second, remove the branch by cutting a couple inches past the undercut (further away from the trunk than the undercut); and third, remove the remaining branch stub just outside the branch collar.</p>

<p>Do not apply paint or wound dressing to cut surfaces. They have been shown to harbor the very pests they were designed to keep out. Further they are expensive and the tree doesn’t need them.</p>

<p>A final note on trees: never top a tree! Topping trees causes serious injury and can lead to a higher risk of failure through disease or decay in the future as the inside of the tree decays from the topping procedure. A tree that has been topped should be inspected by a certified arborist to evaluate its potential risk for failure.</p>

<p>When to prune, how much, and how to prune are not the same for all types of plants and may depend on the space, the desired shape and personal aesthetic preferences. This article just outlines the basics.</p>

<h6>For more information, there are a few options:</h6>

<ul>
	<li>Check the Garden’s programs for classes pertaining to your particular need</li>
	<li>Volunteer with the horticulture department and learn hands-on or for more information on pruning trees here</li>
	<li>A Few good websites:</li>
	<ul>
		<li><a href="http://www.forestry.uga.edu/warnell/service/library">http://www.forestry.uga.edu/warnell/service/library</a></li>
		<li><a href="http://hort.ufl.edu/woody/pruning">http://hort.ufl.edu/woody/pruning</a></li>
	</ul>
</ul>

<p>For some information on selecting an arborist, refer to the <a href="/selecting-a-qualified-arborist">Selecting a Qualified Arborist article</a>.</p>
	
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