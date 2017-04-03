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
<title>Past Concerts | Red Butte Garden</title>
    

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
		<div class="grid-header">PAST RED BUTTE GARDEN CONCERTS</div>		
	<hr>
</div>
<br />
		<!-- Begin 2016 -->
		<div class="row">
			
			<div class="col-sm-5">	
	
				<center>
				<br />
				<a href="/images/concert-images/lineup-images/2016-lineup.jpg" target="_blank">	
								        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2016-lineup.jpg">
								        </a>
				<br />
				</center>	
							        
			</div>

			
			<div class="col-sm-7" class="text-center">	
			
				<h3 class="text-center">2016</h3>
				
					<li>	The Lumineers with special guests SOAK, Sleepwalkers</li>
					<li>	Buddy Guy &amp; Jonny Lang</li>
					<li>	The Monkees 50th Anniversary Tour</li>
					<li>	Edward Sharpe and the Magnetic Zeros with special guests Preservation Hall Jazz Band, Harriet</li>
					<li>	Ben Harper &amp; The Innocent Criminals with special guest The Jack Moves</li>
					<li>	case/lang/veirs with special guest LOCH LOMOND </li>
					<li>	Barenaked Ladies with OMD &amp; Howard Jones </li>
					<li>	JJ Grey &amp; Mofro / Josh Ritter / special guest HONEY HONEY</li>
					<li>	Boz Scaggs with special guest Jeff LeBlanc</li>
					<li> 	The Avett Brothers with special guest Cory Mon</li>
					<li> 	Willie Nelson &amp; Family with special guest Tony Holiday</li>
					<li> 	Gary Clark Jr. with special guest The Weekenders</li>
					<li> 	Weird Al Yankovic</li>
					<li> 	Tedeschi Trucks Band with Los Lobos &amp; North Mississippi Allstars</li>
					<li>	Culture Club with special guest GROVES</li>
					<li>	Michael Franti & Spearhead with special guest Dustin Thomas</li>
					<li>	Pablo Villegas with the Utah Symphony</li>
					<li>	Lake Street Dive with special guest Gregory Alan Isakov</li>
					<li>	Ryan Adams with special guest Amanda Shires</li>
					<li>	Pat Benatar & Neil Giraldo / Melissa Etheridge</li>
					<li>	Grace Potter with special guest Con Brio</li>
					<li>	Old Crow Medicine Show with special guest Dom Flemons</li>
					<li>	Jackson Browne</li>
					<li>	Wilco with special guest Joan Shelley</li>
					<li>	Blondie with special guest Desi Valentine</li>
					<li>	Kacey Musgraves with special guest Sam Outlaw</li>
					<li>	Bonnie Raitt with special guest Richard Thompson Trio</li>
					<li>	NEEDTOBREATHE with Mat Kearney, John Mark McMillan, Welshly Arms</li>
					<li>	Goo Goo Dolls with special guests Collective Soul and Tribe Society</li>
					<li>	Jason Isbell with special guest Margaret Glaspy</li>
					<li>	Tears For Fears with special guest Zipper Club</li>

			</div>
			
		</div>
		<!-- End 2016 -->
		
		<br />
		<hr>
		
		<!-- Begin 2015 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2015</h3>
			
					<li>	Passion Pit with special guest HOLYCHILD</li>
					<li>	The Decemberists with special guest Wartime Blues</li>
					<li>	Chromeo and ODESZA with CLASSIXX</li>
					<li>	Lindsey Stirling with special guests KARMIN and Melissa Martinez</li>
					<li>	Ryan Adams with special guest Wardell</li>
					<li>	Tedeschi Trucks Band, Sharon Jones & the Dap Kings with special guest Doyle Bramhall II</li>
					<li>	Cooder-White-Skaggs with special guest Robert Earl Keen</li>
					<li>	Rob Thomas with special guests Plain White T's and Black Vinyl</li>
					<li>	Brian Wilson with special guest Rodriguez</li>
					<li>	Hank Williams, Jr. with special guest Sam Riddle</li>
					<li>	Sweet Harmony Soul featuring Mavis Staples, Patty Griffin and Amy Helm & the Handsome Strangers</li>
					<li>	Steve Miller Band with special guest Daniel Young Buehner</li>
					<li>	Harry Connick, Jr.</li>
					<li>	Lyle Lovett and his Large Band</li>
					<li>	Under The Sun Tour with Sugar Ray, Better Than Ezra, Uncle Kracker, EVE 6</li>
					<li>	Alabama Shakes with special guest Chicano Batman</li>
					<li>	Michael Franti & Spearhead with special guest The Movement</li>
					<li>	John Fogerty</li>
					<li>	Trampled By Turtles & The Devil Makes Three</li>
					<li>	The Utah Symphony with Time For Three</li>
					<li>	Brandi Carlile with special guest Anderson East</li>
					<li>	Rodrigo y Gabriela with special guest Heather Maloney</li>
					<li>	Wilco with special guest Vetiver</li>
					<li>	Orquesta Buena Vista Social Club with special guest David Wax Museum</li>
					<li>	Garrison Keillor's A Prairie Home Companion - America The Beautiful Tour</li>
					<li>	YES and TOTO</li>
					<li>	An Evening with CAKE</li>
					<li>	An Evening with Mark Knopfler</li>
					<li>	An Evening with Ben Harper & The Innocent Criminals</li>
	
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<a href="/images/concert-images/lineup-images/2015-lineup.jpg" target="_blank">	
							        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2015-lineup.jpg">
							        </a>
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2015-->
		
		<br />
		<hr>
		
		<!-- Begin 2014 -->
		<div class="row">
			
			<div class="col-sm-5">	
	
				<center>
				<br />
				<a href="/images/concert-images/lineup-images/2014-lineup.jpg" target="_blank">	
								        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2014-lineup.jpg">
								        </a>
				<br />
				</center>	
							        
			</div>

			
			<div class="col-sm-7" class="text-center">	
			
				<h3 class="text-center">2014</h3>
				
					<li>	Emmylou Harris with special guest Nathaniel Rateliff </li>
					<li>	Janelle Monáe with special guest Conner Youngblood</li>
					<li>	Jason Isbell with special guest The Lone Bellow</li>
					<li>	The Robert Cray Band / Mavis Staples</li>
					<li>	Natalie Cole with special guest Joy & Eric</li>
					<li>	Gavin DeGraw and Matt Nathanson with special guest Mary Lambert</li>
					<li>	Fitz and the Tantrums with special guests Max Frost & HOLYCHILD</li>
					<li>	Sarah McLachlan Shine On Tour 2014</li>
					<li>	The Avett Brothers with special guest Nicole Atkins</li>
					<li>	Bob Weir & RatDog</li>
					<li>	Pat Metheny Unity Group & Bruce Hornsby w/Sonny Emory - Campfire Tour 2104</li>
					<li>	Tedeschi Trucks Band with special guest Rich Robinson</li>
					<li>	Lyle Lovett & his Large Band</li>
					<li>	Gary Clark Jr. with special guest Black Pistol Fire</li>
					<li>	Amos Lee with special guest Desert Noises</li>
					<li>	Santana</li>
					<li>	John Hiatt and The Combo & Taj Mahal Trio</li>
					<li>	Chris Isaak with special guest Morgan Snow</li>
					<li>	John Butler Trio with special guest The Stray Sisters</li>
					<li>	Ray LaMontagne with special guest The Belle Brigade</li>
					<li>	Trombone Shorty and Orleans Avenue / Galactic</li>
					<li>	Michael McDonald & TOTO</li>
					<li>	Sheryl Crow with special guest Cam</li>
					<li>	Portugal. The Man & Grouplove</li>
					<li>	David Gray with special guest David Kitt</li>
					<li>	Brandi Carlile with special guest Hollow Wood</li>
					<li>	Earth, Wind & Fire</li>
					<li>	An Acoustic Evening with Ben Harper</li>
					<li>	Conor Oberst with Jonathan Wilson</li>
			</div>
			
		</div>
		<!-- End 2014 -->
		
		<br />
		<hr>
		
		<!-- Begin 2013 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2013</h3>
			
					<li>	Vampire Weekend with The High Highs</li>
					<li>	Edward Sharpe & The Magnetic Zeros</li>
					<li>	Trombone Shorty & Orleans Avenue / Big Head Todd and the Monsters</li>
					<li>	Grace Potter and the Nocturnals with Lukas Nelson & Promise of the Real</li>
					<li>	Jackson Brown with Sara Watkins</li>
					<li>	Tony Bennett</li>
					<li>	Tedeschi Trucks Band with Rayland Baxter</li>
					<li>	She & Him with Tilly and the Wall</li>
					<li>	Old Crow Medicine Show with Parker Millsap</li>
					<li>	Pink Martini</li>
					<li>	Rodrigo y Gabriela with Alex Wilson</li>
					<li>	Brandi Carlile with The Lone Bellow</li>
					<li>	David Byrne & St. Vincent</li>
					<li>	Garrison Keillor's A Prairie Home Companion Radio Romance Tour</li>
					<li>	Kenny Loggins with Blue Sky Riders</li>
					<li>	Dwight Yoakam with The Hollering Pines</li>
					<li>	Merle Haggard with Paul Thorn</li>
					<li>	Medeski Martin Wood / John Scofield Uberjam Band</li>
					<li>	Steve Miller Band with Morgan Snow</li>
					<li>	Steely Dan with Bobby Broom and The Deep Blue Organ Trio</li>
					<li>	John Butler Trio with Zach Heckendorf</li>
					<li>	Michael Franti & Spearhead with Ethan Tucker and Amanda Shaw</li>
					<li>	John Prine with Johnnyswim</li>
					<li>	George Thorogood and the Destroyers / Buddy Guy</li>
					<li>	Wayne Shorter 80th Birthday Celebration (Wayne Shorter Quartet, Joe Lovano & Dave Douglas Quintet, ACS: Allen, Carrington, Spalding)</li>
					<li>	The Black Crowes</li>
					<li>	Neko Case	with Pickwick</li>
	
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<a href="/images/concert-images/lineup-images/2013-lineup.jpg" target="_blank">	
							        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2013-lineup.jpg">
							        </a>
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- Begin 2013 -->
		
		<br />
		<hr>
		
		<!-- Begin 2012 -->
		<div class="row">
			
			<div class="col-sm-5">	
	
				<center>
				<br />
				<a href="/images/concert-images/lineup-images/2012-lineup.jpg" target="_blank">	
								        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2012-lineup.jpg">
								        </a>
				<br />
				</center>	
							        
			</div>

			
			<div class="col-sm-7" class="text-center">	
			
				<h3 class="text-center">2012</h3>
					
					<li>	The Shins with The Head and The Heart and Blind Pilot</li>
					<li>	Bon Iver with The Staves</li>
					<li>	Sheryl Crow with Amy Levere</li>
					<li>	American Legacies: Preservation Hall Jazz Band & Del McCoury Band</li>
					<li>	Melissa Etheridge</li>
					<li>	Wilco with Blitzen Trapper</li>
					<li>	Jimmy Cliff with Trevor Hall</li>
					<li>	The B-52s & Squeeze</li>
					<li>	Brandi Carlile with You, Me & Apollo</li>
					<li>	Josh Ritter & The Royal City Band with Joe Purdy</li>
					<li>	Steve Martin & The Steep Canyon Rangers - An Evening of Bluegrass & Comedy</li>
					<li>	Grace Potter and the Nocturnals with ZZ Ward</li>
					<li>	Al Green with joy&eric</li>
					<li>	Los Lobos & Steve Earle and the Dukes (and Duchesses) featuring Allison Moorer</li>
					<li>	Diana Krall with Denzal Sinclaire</li>
					<li>	Colbie Caillat & Gavin DeGraw</li>
					<li>	Michael Franti & Spearhead with Zach Heckendorf</li>
					<li>	Gipsy Kings</li>
					<li>	Andrew Bird with Amadou & Mariam</li>
					<li>	Dead Can Dance</li>
					<li>	Norah Jones with Cory Chisel and The Wandering Sons</li>
					<li>	Crosby, Stills & Nash</li>
					<li>	Huey Lewis & The News with Katie Todd</li>
					<li>	Bonnie Raitt with Special Guest Mavis Staples -- Night 1</li>
					<li>	Bonnie Raitt with Special Guest Mavis Staples -- Night 2</li>
					<li>	Trombone Shorty & Orleans Avenue with The Stone Foxes</li>
					<li>	The Piano Guys</li>
			</div>
			
		</div>
		<!-- End 2012 -->
		
		<br />
		<hr>
		
		<!-- Begin 2011 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2011</h3>
			
					<li>	The Moody Blues</li>
					<li>	Big Head Todd & the Monsters / Toots & the Maytals</li>
					<li>	CAKE</li>
					<li>	Buddy Guy with Mavis Staples</li>
					<li>	Ani DiFranco with Greg Brown</li>
					<li>	Sheryl Crow</li>
					<li>	Pink Martini</li>
					<li>	Michael Franti & Spearhead</li>
					<li>	Sharon Jones and the Dap Kings with Buckwheat Zydeco</li>
					<li>	Josh Ritter & The Royal City Band with Blind Pilot and The Devil Makes Three</li>
					<li>	Fleet Foxes with Alela Diane and Wild Divine</li>
					<li>	Steve Miller Band</li>
					<li>	Bruce Hornsby & The Noisemakers / Bela Fleck & The Flecktones</li>
					<li>	Lyle Lovett and his Large Band</li>
					<li>	k.d. lang & The Siss Boom Bang</li>
					<li>	Jerry Jeff Walker with James Cotton Superharp</li>
					<li>	G. Love & Special Sauce with Trombone Shorty & Orleans Avenue</li>
					<li>	Jonny Lang / JJ Grey & Mofro</li>
					<li>	Gipsy Kings featuring Nicolas Reyes and Tonino Baliardo</li>
					<li>	Peter Frampton</li>
					<li>	Brandi Carlile with Ivan and Alyosha</li>
					<li>	Return to Forever IV with Dweezil Zappa Plays Zappa</li>
					<li>	Thievery Corporation with Shana Halligan</li>
					<li>	Alison Krauss & Union Station featuring Jerry Douglas with Dawes</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<a href="/images/concert-images/lineup-images/2011-lineup.jpg" target="_blank">	
							        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2011-lineup.jpg">
							        </a>
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2011 -->
		
		<br />
		<hr>
		
		<!-- Begin 2010 -->
		<div class="row">
			
			<div class="col-sm-5">	
	
				<center>
				<br />
				<a href="/images/concert-images/lineup-images/2010-lineup.jpg" target="_blank">	
								        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2010-lineup.jpg">
								        </a>
				<br />
				</center>	
							        
			</div>

			
			<div class="col-sm-7" class="text-center">	
			
				<h3 class="text-center">2010</h3>
					
				<li>	Kenny Wayne Shepherd with Blues on First</li>
				<li>	Steve Martin & The Steep Canyon Rangers with the Punch Brothers (featuring Chris Thile)</li>
				<li>	Joss Stone with Josh Charles</li>
				<li>	Chicago with Joy & Eric</li>
				<li>	JJ Grey & MOFRO with Todd Snider & Great American Taxi</li>
				<li>	Joan Baez with Guy Clark</li>
				<li>	Brandi Carlile with Katie Herzig</li>
				<li>	Barenaked Ladies with Kris Allen</li>
				<li>	Lyle Lovett & his Large Band</li>
				<li>	Rhythm Devils (featuring Mickey Hart, Bill Kreutzmann, Keller Williams, Sikiru Adepoju, Davy Knowles & Andy Hess)</li>
				<li>	Mary Chapin Carpenter with Garrison Starr</li>
				<li>	Natalie Merchant</li>
				<li>	Allen Toussaint with Dirty Dozen Brass Band, Trombone Shorty & Orleans Avenue</li>
				<li>	Chris Isaak with Mia Dyson</li>
				<li>	The Swell Season with Peter Salett</li>
				<li>	John Prine with Carrie Rodriguez</li>
				<li>	Norah Jones with Corrine Bailey Rae</li>
				<li>	A Prairie Home Companion (featuring Garrison Keillor & Sara Watkins)</li>
				<li>	Doobie Brothers with Libbie Linton</li>
				<li>	Sheryl Crow with Colbie Caillat</li>
				<li>	Willie Nelson with Chuck Mead</li>
				
			</div>
			
		</div>
		<!-- End 2010 -->
		
		<br />
		<hr>
		
		<!-- Begin 2009 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2009</h3>
			
				<li>	Neko Case with Joey & John of Calexico</li>
				<li>	Etta James & The Roots Band</li>
				<li>	Femi Kuti with Bela Fleck & Toumani Diabate</li>
				<li>	Smokey Robinson</li>
				<li>	David Byrne</li>
				<li>	Indigo Girls</li>
				<li>	Death Cab for Cutie with Andrew Bird & Ra Ra Riot</li>
				<li>	The Wallflowers with Vedera</li>
				<li>	Diana Krall</li>
				<li>	Chicago</li>
				<li>	Chris Isaak</li>
				<li>	Los Lobos & Los Lonely boys</li>
				<li>	The Pretenders with Cat Power & Juliette Lewis</li>
				<li>	The Avett Brothers with the Heartless Bastards</li>
				<li>	Bonnie Raitt & Taj Mahal</li>
				<li>	Booker T. & The Drive By Truckers</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<a href="/images/concert-images/lineup-images/2009-lineup.jpg" target="_blank">	
							        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2009-lineup.jpg">
							        </a>
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2009 -->
		
		<br />
		<hr>
		
		<!-- Begin 2008 -->
		<div class="row">
			
			<div class="col-sm-5">	
	
				<center>
				<br />
				<a href="/images/concert-images/lineup-images/2008-lineup.jpg" target="_blank">	
								        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2008-lineup.jpg">
								        </a>
				<br />
				</center>	
							        
			</div>

			
			<div class="col-sm-7" class="text-center">	
			
				<h3 class="text-center">2008</h3>
					
				<li>	Jazz at Lincoln Center Orchestra with Wynton Marsalis</li>
				<li>	Jonny Lang</li>
				<li>	Emmylou Harris</li>
				<li>	Derek Trucks & Susan Tedeschi with Scrapomatic</li>
				<li>	Los Lonely Boys & Los Lobos</li>
				<li>	Greg Brown with Iris DeMent & Pieta Brown</li>
				<li>	Wilco with Fleet Foxes</li>
				<li>	A Prairie Home Companion with Garrison Keillor</li>
				<li>	KT Tunstall with Martha Wainwright</li>
				<li>	John Hiatt & The Ageless Beauties with Joan Osborne</li>
				<li>	Bonnie Raitt with Leo Kottke</li>
				<li>	Bonnie Raitt with Richard Julian</li>
				<li>	Al Green</li>
				<li>	G. Love & Special Sauce with John Butler Trio & Tristan Prettyman</li>			
			</div>
			
		</div>
		<!-- End 2008 -->
		
		<br />
		<hr>
		
		<!-- Begin 2007 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2007</h3>
			
				<li>	Derek Trucks & Susan Tedeschi</li>
				<li>	Indigo Girls</li>
				<li>	Chick Corea & Bela Fleck</li>
				<li>	Ricky Skaggs & Kentucky Thunder</li>
				<li>	The Neville Brothers & Sonny Landreth</li>
				<li>	Chris Isaak</li>
				<li>	Mavis Staples & Bettye LaVette</li>
				<li>	Ryan Adams & The Cardinals</li>
				<li>	Sierra Leone's Refugee All Stars</li>
				<li>	Keb' Mo' & Robert Cray</li>
				<li>	Bruce Hornsby</li>
				<li>	Son Volt & Alejandro Escovedo</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<a href="/images/concert-images/lineup-images/2007-lineup.jpg" target="_blank">	
	        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/2007-lineup.jpg">
	        </a>
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2007 -->
		
		<br />
		<hr>
		
		<!-- Begin 2006 -->
		<div class="row">
		
			<div class="col-sm-5">	
			<center>
			<br />
			<!-- Find poster
			<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
				<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
			</a>
			-->
			<br />
			</center>				        
			</div>		
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2006</h3>
			
				<li>The Del McCoury Band</li>
				<li>Joe Jackson</li>
				<li>John Hiatt & The North Mississippi Allstars</li>
				<li>Jonny Lang</li>
				<li>Indigo Girls</li>
				<li>Koko Taylor & Her Blues Machine</li>
				<li>James McMurtry & Hot Tuna</li>
				<li>Suzanne Vega</li>
				<li>Herbie Hancock</li>
				<li>Nickel Creek</li>
				<li>Dr. John</li>
				<li>Rosanne Cash</li>
				
			</div>
			
		</div>
		<!-- End 2006 -->
		
		<br />
		<hr>
		
		<!-- Begin 2005 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2005</h3>
			
				<li>Chris Isaak</li>
				<li>Nanci Griffith</li>
				<li>Flatlanders</li>
				<li>Lyle Lovett</li>
				<li>Fabulous Thunderbirds</li>
				<li>Cowboy Junkies</li>
				<li>Bruce Hornsby</li>
				<li>Julie Roberts</li>
				<li>John Hiatt & Shawn Colvin</li>
				<li>Steve Earle</li>
				<li>Susan Tedeschi	with The Blind Boys of Alabama</li>
				<li>Kasey Chambers</li>
				<li>Jonny Lang</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<!-- Find poster
			<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
	        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
	        </a>
	        -->
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2005 -->
		
		<br />
		<hr>
		
		<!-- Begin 2004 -->
		<div class="row">
		
			<div class="col-sm-5">	
			<center>
			<br />
			<!-- Find poster
			<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
	        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
	        </a>
	        -->
			<br />
			</center>				        
			</div>
			
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2004</h3>
			
				<li>Mary Chapin Carpenter</li>
				<li>John Hiatt</li>
				<li>The Robert Cray Band</li>
				<li>Marcia Ball</li>
				<li>Cassandra Wilson</li>
				<li>Quetzal</li>
				<li>Ani DiFranco</li>
				<li>The Blind Boys of Alabama</li>
				<li>George Thorogood & The Destroyers</li>
				<li>The Sweet Harmony Traveling Revue featuring Emmylou Harris, Patty Griffin, Buddy Miller, Gillian Welch, and David Rawlings.</li>
				<li>Lyle Lovett</li>
				<li>Joan Osborne</li>
				
			</div>
	
		</div>
		<!-- End 2004 -->
		
		<br />
		<hr>				

		<!-- Begin 2003 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2003</h3>
			
				<li>Susan Tedeschi</li>
				<li>Robert Earl Keen</li>
				<li>Taj Mahal and the Hula Blues Band</li>
				<li>They Might Be Giants</li>
				<li>Shawn Colvin</li>
				<li>Lucinda Williams</li>
				<li>Norah Jones</li>
				<li>Los Lobos</li>
				<li>Keb' Mo'</li>
				<li>k.d. lang</li>
				<li>Ralph Stanley</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<!-- Find poster
			<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
	        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
	        </a>
	        -->
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2003 -->
		
		<br />
		<hr>
		
		<!-- Begin 2002 -->
		<div class="row">

			<div class="col-sm-5">	
				<center>
				<br />
				<!-- Find poster
				<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
		        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
		        </a>
		        -->
				<br />
				</center>				        
			</div>
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2002</h3>
			
				<li>Nanci Griffith</li>
				<li>Cowboy Junkies</li>
				<li>John Hiatt</li>
				<li>Indigo Girls</li>
				<li>Bruce Hornsby</li>
				<li>Jerry Jeff Walker</li>
				<li>Femi Kuti</li>
				<li>Nickel Creek</li>
				<li>Bela Fleck & the Flecktones</li>
				
			</div>
			
		</div>
		<!-- End 2002 -->
		
		<br />
		<hr>		

		<!-- Begin 2001 -->
		<div class="row">
		
			<div class="col-sm-7" class="text-center">	
			
			<h3 class="text-center">2001</h3>
			
				<li>Bruce Hornsby</li>
				<li>Keb' Mo'</li>
				<li>Indigo Girls</li>
				<li>Asleep At The Wheel</li>
				<li>Los Lobos</li>
				<li>Lucinda Williams</li>
				<li>BeauSoleil</li>
				<li>Leon Russell</li>
				<li>Buddy Guy</li>
				
			</div>
			
			<div class="col-sm-5">	
			<center>
			<br />
			<!-- Find poster
			<a href="/images/concert-images/lineup-images/.jpg" target="_blank">	
	        	<img class="responsive" style="max-width: 350px"src="/images/concert-images/lineup-images/.jpg">
	        </a>
	        -->
			<br />
			</center>				        
			</div>
	
		</div>
		<!-- End 2001 -->
		
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