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
<title>Membership FAQ | Red Butte Garden</title>
    

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
		<div class="grid-header">MEMBERSHIP FAQ</div>		
	<hr>
</div>

<br />

<p class="text-center"><strong>Need more information about Red Butte Garden Membership? Check out our Frequently Asked Questions below.</strong></p>

<h2 class="green text-center">General Questions</h2>
				
<div class="panel-group" id="accordion01">
				  
	<!-- Question 1 Start -->
	<div class="panel panel-default">
	  <a data-toggle="collapse" data-parent="#accordion01" href="#Q1">
	  	<div class="panel-heading">
	        <div class="panel-title">What is the best way to purchase or renew a membership?</div>
		</div>
	  </a>
	  <div id="Q1" class="panel-collapse collapse in">
	    <div class="panel-body"><p>Memberships may be purchased multiple ways:<br/>
			<ul>
				<li><a href="https://55218.blackbaudhosting.com/55218/Garden-Membership">ONLINE</a> with a credit card</li>
				<li>By phone with a credit card: 801-585-7172</li>
				<li>In person at the RBG Visitor Center with cash, check, or credit card: 300 Wakara Way, Salt Lake City, UT 84108</li>				
				<li>With a check by mail:<br/><br/>
			<b>Print out, fill out, and return this Membership Application <a href="http://www.redbuttegarden.org/sites/default/files/Membership%20Application_0.pdf" title="">FORM</a> to:</b><br/>
			<i>Red Butte Garden, Attn: Membership Dept.<br/>
			300 Wakara Way, Salt Lake City, UT 84108</i></li>
			</ul> 
			</p></div>
	  </div>
	</div>
	
	<!-- Question 2 Start -->
	<div class="panel panel-default">
	  <a data-toggle="collapse" data-parent="#accordion01" href="#Q2">
	  	<div class="panel-heading">
	    	<div class="panel-title">My friend / family / coworker loves Red Butte Garden! How can I give them the gift of membership?</div>
		</div>
		  </a>
	  <div id="Q2" class="panel-collapse collapse">
	    <div class="panel-body">
	    <p>
			<ul>
				<li>Gift Memberships can be purchased <a href="https://55218.blackbaudhosting.com/55218/Garden-Membership">ONLINE</a>, by phone at <b>801-585-7172</b>, or in person at the RBG Visitor Center. <span style="color:#FF0000;">Gift Memberships cannot be purchased through the mail.</span></li>
				<li>When purchasing a Gift Membership online ensure you check the box <i>“This membership is a gift”</i> and complete all requested fields to ensure the gift is mailed in a timely manner.</li>
			</ul>
		</p>
		</div>
	  </div>
	</div>
	
	<!-- Question 3 Start -->
	<div class="panel panel-default">
	  <a data-toggle="collapse" data-parent="#accordion01" href="#Q3">
	  	<div class="panel-heading">
	    	<div class="panel-title">When can I expect to receive my membership card?</div>
	    </div>
	  </a>
	  <div id="Q3" class="panel-collapse collapse">
	    <div class="panel-body">
	    	<p>Please allow three to four weeks for your card to arrive, but don’t wait to enjoy the Garden! During the processing period you may continue to visit by simply showing a photo ID at the RBG Visitor Center.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question 4 Start -->
	<div class="panel panel-default">
	  <a data-toggle="collapse" data-parent="#accordion01" href="#Q4">
	  	<div class="panel-heading">
	    	<div class="panel-title">How often do membership prices increase? Why?</div>
		</div>
	  </a>
	  <div id="Q4" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Membership rates increase every two to three years. Periodically assessing the membership program and increasing rates allows the Garden to both provide an excellent experience to members and ensure prices cover the increasing cost of fulfilling membership benefits.</p>
	    </div>
	  </div>
	</div>
	
	
					    				    
	<!-- Question 20 Start -->
	<div class="panel panel-default">
	  	<a data-toggle="collapse" data-parent="#accordion01" href="#Q20">
		  	<div class="panel-heading">
			  	<div class="panel-title">Is my membership gift tax-deductible? If so, how do I get my receipt?</div>
			</div>
		</a>
	  <div id="Q20" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Memberships of $75 or less are 100% tax-deductible. Memberships more than $75 are tax-deductible, less the fair market value of any benefits you may receive.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question 21 Start -->
	<div class="panel panel-default">
	  	<a data-toggle="collapse" data-parent="#accordion01" href="#Q21">
		  	<div class="panel-heading">
			  	<div class="panel-title">Can membership gifts be matched?</div>
			</div>
		</a>
	  <div id="Q21" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Yes! Find out if your employer matches gifts <a href="http://giving.utah.edu/matchinggifts/">HERE</a>, or contact your employers’ Human Resources Department.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question 22 Start -->
	<div class="panel panel-default">
	  	<a data-toggle="collapse" data-parent="#accordion01" href="#Q22">
		  	<div class="panel-heading">
			  	<div class="panel-title">I lost my membership card! What should I do?</div>
			</div>
		</a>
	  <div id="Q22" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Contact the Membership Department at <a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a> or call <b>801-585-7172</b> to request a replacement. You should receive your new card within three to four weeks. While waiting for your new card, continue to visit the Garden by simply showing your photo ID at the Visitor Center.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question 23 Start -->
	<div class="panel panel-default">
	  	<a data-toggle="collapse" data-parent="#accordion01" href="#Q23">
		  	<div class="panel-heading">
			  	<div class="panel-title">If I renew my membership before it expires, how will this affect my expiration date?</div>
			</div>
		</a>
	  <div id="Q23" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Your membership is valid for 12 full months. If you renew your Membership early, your membership will be extended for 12 months past your current expiration date.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question 24 Start -->
	<div class="panel panel-default">
		  <a data-toggle="collapse" data-parent="#accordion01" href="#Q24">
		  	<div class="panel-heading">
		    	<div class="panel-title">I work with a non-profit, and would love to include a Red Butte Garden membership in our charity auction. How can I apply for a donation?</div>
			</div>
		  </a>
		  <div id="Q24" class="panel-collapse collapse">
		    <div class="panel-body">
		        <p>We love helping out our community! See the Garden’s <a href="https://redbuttegarden.formstack.com/forms/donation_request_form">DONATION REQUEST</a> page for instructions. </p>
		    </div>
		  </div>
		 </div>
	
	<!-- Question Start -->
	<div class="panel panel-default">
	  	<a data-toggle="collapse" data-parent="#accordion01" href="#Q25">
		  	<div class="panel-heading">
			  	<div class="panel-title">Where can I find a complete list of membership policies?</div>
			</div>
		</a>
	  <div id="Q25" class="panel-collapse collapse">
	    <div class="panel-body">
	        <p>Check out our Garden Membership <a href="#mempoliciesheader" data-target="#mempolicies" data-toggle="collapse">POLICIES</a> page.</p>
	    </div>
	  </div>
	</div>
	
	<!-- Question Start -->
	<div class="panel panel-default">
	  <a data-toggle="collapse" data-parent="#accordion01" href="#QEmail">
	  	<div class="panel-heading">
	    	<div class="panel-title">I’m not receiving Red Butte emails but your staff said they have been sent. How do I add Red Butte Garden as a safe sender to my email?</div>
	    </div>
	  </a>
	  <div id="QEmail" class="panel-collapse collapse">
	    <div class="panel-body">
	    
	    	<p><a href="/documents/mark-email-as-safe.pdf">Please click here and follow the instructions in the document to mark garden email as safe</a></p>
	    
	    </div>
	  </div>
	</div>
				    
</div>

<br />

<h2 class="green text-center">Concerts</h2>

<!-- Begin Concert Questions Panel -->
<div class="panel-group" id="accordion02">

			<!-- Question 11 Start -->
			<div class="panel panel-default">
		    	<a data-toggle="collapse" data-parent="#accordion02" href="#Q11">
		      		<div class="panel-heading">
		        		<div class="panel-title">What membership levels are eligible for Red Butte Garden Outdoor Concert Series benefits?</div>
					</div>
				</a>
				<div id="Q11" class="panel-collapse collapse in">
			        <div class="panel-body">
			        	<p>You must purchase a <span class="lilac">Garden-Plus</span> level or above to qualify for concert benefits. <span style="color:#FF0000;">Garden-Basic does not receive concert benefits.</span></p>
			        </div>
				</div>
		    </div>
		    
		    <!-- Question 12 Start -->
			<div class="panel panel-default">
		      <a data-toggle="collapse" data-parent="#accordion02" href="#Q12">
		      		<div class="panel-heading">
		      			<div class="panel-title">How does the Garden member-only presale of tickets for the Outdoor Concert Series work?</div>
			  		</div>
		      </a>
		      <div id="Q12" class="panel-collapse collapse">
		        <div class="panel-body">
			        <p>Current members at the <span class="lilac">Garden-Plus</span> level and above are eligible to participate in the concert series presale one week before tickets go on sale to the public. Generally the presale takes place at the end of April.</p>
			<p>The Membership promo code is the email address associated with your Garden membership. This code allows members to purchase presale tickets and get a discount.</p>
			<p>It is wise to ensure your Garden membership is current by the month of March, so that no problems are encountered. For more information on the Garden member presale, visit the <a href="#">HOW TO BUY</a> concert tickets page.</p>
				</div>
		      </div>
		    </div>
		    
		    <!-- Question 13 Start -->
			<div class="panel panel-default">
		      <a data-toggle="collapse" data-parent="#accordion02" href="#Q13">
		      		<div class="panel-heading">
		        		<div class="panel-title">How many concert tickets can I purchase at the member rate?</div>
					</div>
		      </a>
		      <div id="Q13" class="panel-collapse collapse">
		        <div class="panel-body">
			        <p>
						<ul>
							<li><span class="lilac">Garden-Plus</span> – 2 member rate tickets per concert</li>
							<li><span class="lilac">Family</span> – 4 member rate tickets per concert</li>
							<li><span class="lilac">Family-Plus</span> – 4 member rate tickets per concert</li>
							<li><span class="lilac">Circle of Friends</span> – 4 member rate tickets per concert</li>
							<li><span class="lilac">Contributor</span> – 6 member rate tickets per concert</li>
							<li><span class="lilac">Forget-Me-Not</span> – 6 member rate tickets per concert</li>
							<li><span class="lilac">Blazing Star</span> – 8 member rate tickets per concert</li>
							<li><span class="lilac">Avant Gardener</span> – 8 member rate tickets per concert</li>
							<li><span class="lilac">Director’s Club</span> – 8 member rate tickets per concert</li>
						</ul>
					</p>
		        </div>
		      </div>
		    </div>
		    
		    <!-- Question 14 Start -->
			<div class="panel panel-default">
		      <a data-toggle="collapse" data-parent="#accordion02" href="#Q14">
		      		<div class="panel-heading">
				  		<div class="panel-title">I want to buy my limit of member rate tickets, but I also need to buy additional tickets at the regular price, can I do that when I buy my discounted tickets?</div>
				  	</div>
		      </a>
		      <div id="Q14" class="panel-collapse collapse">
		        <div class="panel-body">
			        <p>No. Only member-rate tickets may be purchased during the presale period. Additional tickets may be purchased when ticket sales open to the General Public. </p>
		        </div>
		      </div>
		    </div>
		    
		    <!-- Question 15 Start -->
			<div class="panel panel-default">
		      	<a data-toggle="collapse" data-parent="#accordion02" href="#Q15">
		      		<div class="panel-heading">
				  		<div class="panel-title">Does my membership guarantee Outdoor Concert Series tickets?</div>
				  	</div>
				</a>
		      <div id="Q15" class="panel-collapse collapse">
		        <div class="panel-body">
			        <p>No. Each concert has a limited number of tickets and there is always a possibility that tickets will sell out before all members get a chance to place their orders. </p>
		        </div>
		      </div>
		    </div>
		    
		    <!-- Question 16 Start -->
			<div class="panel panel-default">
		      	<a data-toggle="collapse" data-parent="#accordion02" href="#Q16">
		      		<div class="panel-heading">
				  		<div class="panel-title">Do members have special parking privileges?</div>
				  	</div>
				</a>
		      <div id="Q16" class="panel-collapse collapse">
		        <div class="panel-body">
			        <p>No. When visiting the Garden or attending a concert, parking is free, but limited. For more information on concert parking, please visit the <a href="#">CONCERT FAQ</a> page. </p>
		        </div>
		      </div>
		    </div>
		    				

</div>

<br />

<h2 class="green text-center">Membership Levels and Benefits</h2>

<div class="panel-group" id="accordion03">


				    <!-- Question 5 Start -->
				    <div class="panel panel-default">
				      <a data-toggle="collapse" data-parent="#accordion03" href="#Q5">
					  	<div class="panel-heading">
						  	<div class="panel-title">In 2015 I had an Individual or Dual Membership, what level is a good fit for me now that those levels have changed?</div>
						</div>
				      </a>
				      <div id="Q5" class="panel-collapse collapse in">
				        <div class="panel-body"><p>The new level, <span class="lilac">Garden-Plus</span>, is perfect for you! <span class="lilac">Garden-Plus</span> is a hybrid of <span class="lilac">Individual</span> and <span class="lilac">Dual</span>. With this membership you may either bring one unnamed guest each visit, or you may name a second person a cardholder. If you choose to name a second cardholder, any guests you bring will need to pay admission, even if the second cardholder is not present. </p></div>
				      </div>
				    </div>
				    
				    <!-- Question 6 Start -->
  				    <div class="panel panel-default">
				    	<a data-toggle="collapse" data-parent="#accordion03" href="#Q6">
				      		<div class="panel-heading">
				        		<div class="panel-title">If I name a second cardholder on my <span class="lilac">Garden-Plus</span> membership, may I still bring guests to the Garden?</div>
							</div>
						</a>
				      <div id="Q6" class="panel-collapse collapse">
				        <div class="panel-body"><p>No, once a second cardholder is named, only cardholders have free admission.</p></div>
				      </div>
				    </div>
				    
				    <!-- Question 7 Start -->
   				    <div class="panel panel-default">
				      <a data-toggle="collapse" data-parent="#accordion03" href="#Q7">
				      	<div class="panel-heading">
				        	<div class="panel-title">What is the difference between a <span class="lilac">Family</span> and a <span class="lilac">Family-Plus</span> Membership?</div>
						</div>
				      </a>
				      <div id="Q7" class="panel-collapse collapse">
				        <div class="panel-body">
				        	<p>
								<ul>
									<li>A <span class="lilac">Family</span> membership allows for two cardholders and free admission for up to six children, age 17 and under, each visit. This level is perfect for parents or grandparents who bring their family to the Garden frequently.</li>
									<li>A <span class="lilac">Family-Plus</span> membership allows for a third cardholder. Family-Plus is a great solution for families whose caregivers may bring their children to the Garden when their guardians are at work or other engagements.</li>
								</ul> 
							</p>
						</div>
				      </div>
				    </div>
				    
				    <!-- Question 8 Start -->
   				    <div class="panel panel-default">
				      	<a data-toggle="collapse" data-parent="#accordion03" href="#Q8">
				      		<div class="panel-heading">
				        		<div class="panel-title">Can I bring play dates to the Garden with my Family / Family-Plus Membership?</div>
							</div>
						</a>
				      <div id="Q8" class="panel-collapse collapse">
				        <div class="panel-body">
					        <p><span class="lilac">Family</span> and <span class="lilac">Family-Plus </span>memberships are perfect for play dates! Each membership allows for up to six unnamed children each visit. Just remember that additional children or any adults who are not cardholders will be charged an admission fee. </p>
				        </div>
				      </div>
				    </div>
				    
				    <!-- Question 9 Start -->
   				    <div class="panel panel-default">
				      <a data-toggle="collapse" data-parent="#accordion03" href="#Q9">
				      	<div class="panel-heading">
				        	<div class="panel-title">I want to bring additional guests to the Garden. How do I get/use my 50% off guest coupons?</div>
						</div>
				      </a>
				      <div id="Q9" class="panel-collapse collapse">
				        <div class="panel-body">
					        <p>Your 50% off Guest Coupons will be included in your welcome package with your membership card. You must bring the physical coupon to the Garden for your guest to receive 50% off admission. </p>
							<p><b>Each Membership level qualifies for the following number of 50% off Guest Coupons: </b><br/>
								<ul>
									<li><span class="lilac">Garden-Basic</span> – 2</li>
									<li><span class="lilac">Garden-Plus</span> – 2</li>
									<li><span class="lilac">Family</span> – 2</li>
									<li><span class="lilac">Family-Plus</span> – 2</li>
									<li><span class="lilac">Circle of Friends</span> – 2</li>
									<li><span class="lilac">Contributor</span> – 4</li>
									<li><span class="lilac">Forget-Me-Not</span> – 6</li>
									<li><span class="lilac">Blazing Star</span> – 8</li>
									<li><span class="lilac">Avant Gardener</span> – 10</li>
									<li><span class="lilac">Director’s Club</span> – 10</li>
								</ul>
							</p>
				        </div>
				      </div>
				    </div>
				    
				    <!-- Question 10 Start -->
   				    <div class="panel panel-default">
				      	<a data-toggle="collapse" data-parent="#accordion03" href="#Q10">
				      		<div class="panel-heading">
						  		<div class="panel-title">I have decided I want a higher level, how can I upgrade my membership?</div>
						  	</div>
						</a>
				      <div id="Q10" class="panel-collapse collapse">
				        <div class="panel-body">
				        	<p>To upgrade your membership please call <b>801-585-7172</b>, or stop by the Visitor Center. <span style="color:#FF0000;">Memberships cannot be upgraded online or through the mail.</span></p>
				        </div>
				      </div>
				    </div>
				    
				    <!-- Question 17 Start -->
   				    <div class="panel panel-default">
				    	<a data-toggle="collapse" data-parent="#accordion03" href="#Q17">
				      		<div class="panel-heading">
						  		<div class="panel-title">I would like to attend an adult workshop / sign my children up for an activity, how do I get my member discount?</div>
						  	</div>
						</a>
				      <div id="Q17" class="panel-collapse collapse">
				        <div class="panel-body">
					        <p>To receive your discount you will need to <a href="https://55218.blackbaudhosting.com/55218/page.aspx?pid=201">REGISTER</a> in Red Butte Garden’s online portal using the email associated with your membership. Within 2-4 weeks you will also receive a User Registration email reminder, but you may register at any time.</p>
				<p>After you are logged in you will be able to register for classes / workshops / activities and receive your discount. Your discount will be reflected after you add items to your cart, before you complete check-out. Outdoor Concert Series tickets are not purchased through this portal. You can find information on purchasing Outdoor Concert Series tickets <a href="#">HERE.</a></p>
				<p>If your discount is not being reflected please call <b>801-585-7172</b>.</p>
				        </div>
				      </div>
				    </div>
				    
				    <!-- Question 18 Start -->
   				    <div class="panel panel-default">
				      	<a data-toggle="collapse" data-parent="#accordion03" href="#Q18">
				      		<div class="panel-heading">
						  		<div class="panel-title">I signed up for a class through the online portal and didn’t receive my discount. What should I do?</div>
						  	</div>
						</a>
				      <div id="Q18" class="panel-collapse collapse">
				        <div class="panel-body">
					        <p>Please call <b>801-581-8454</b>. Staff will work with you to ensure you are refunded the proper amount, and that future registrations are processed properly. </p>
				        </div>
				      </div>
				    </div>
				    
				    <!-- Question 19 Start -->
   				    <div class="panel panel-default">
				      	<a data-toggle="collapse" data-parent="#accordion03" href="#Q19">
						  	<div class="panel-heading">
							  	<div class="panel-title">I never received my user registration email for the online portal. How do I get set up to get my membership discount on Garden programming?</div>
							</div>
						</a>
				      <div id="Q19" class="panel-collapse collapse">
				        <div class="panel-body">
					        <p>You can <a href="https://55218.blackbaudhosting.com/55218/page.aspx?pid=201">REGISTER</a> on our website. Just remember to use the email associated with your membership so the system will properly recognize you and give you your benefits. If you continue to encounter issues, please call <b>801-585-7172</b>.</p>
				        </div>
				      </div>
				    </div>

</div>

<br/>
				
<center>
	<h4>More Questions?</h4>
	<p><a href="mailto:membership@redbutte.utah.edu">membership@redbutte.utah.edu</a></p>
	<p>Call <b>801-585-7172</b></p>
</center>
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