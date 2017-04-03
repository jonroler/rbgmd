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

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
      <title>Enjoy the Garden | Red Butte Garden</title>
  {% include favicon.html %}
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Open+Sans" /> <!-- Font 'Open Sans' Hosted by Google -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>

  <link rel="stylesheet" href="/CSS/summer.css?v=1"> <!-- Additional local CSS -->
  
</head>
<body>

{% include facebook-plugin.html %}

{% include navbar.html %}

<div id="slider-wrapper">

    <div id="inner-slider-wrapper1">
    <div id="inner-slider-wrapper2">
    
        <!-- Jssor Slider Begin -->
        <div id="slider1_container">
            <!-- Slides Container -->
            <div id="slides" u="slides">
            
            {% include eventslides.html %}
            
            </div>
            
            <!-- bullet navigator container -->
            <div u="navigator" class="jssorb21" style="top: 68px;">
                <!-- bullet navigator item prototype -->
                <div u="prototype"></div>
            </div>
            
            <!-- Arrow Left -->
            <span u="arrowleft" class="jssora21l" style="top: 123px; left: 8px;"></span>
            
            <!-- Arrow Right -->
            <span u="arrowright" class="jssora21r" style="top: 123px; right: 8px;"></span>
            
        </div>
        <!-- Jssor Slider End -->
                            
        <!-- Begin Page Down Code -->
		<div id="page-down2" class="col-xs-12">
			<span class="page-down-icon"><img src="/images/core/down-arrow.png" /></span>
			<!-- Code for Sprite Option -->
			<!-- <span class="page-down-icon" style="background-color:red;"><span class="jssora21l"></span></span> -->
		</div>
		<!-- End Page Down Code -->
        
    </div>
    </div>
    <!-- Begin Inner Info Div -->
    <div id="rbg-info-wrapper1">
	<div id="rbginfobg">
	
		<div id="rbginfo" class="row-fluid clearfix">
					
			<div id="rbghours" class="col-xs-3"><a href="/general-info"><div class="rbghours hover"></div></a>
				<div id="gardenHours"></div>
				<div id="gardenStatus"></div>
				<div id="otherNotes"></div>
			</div>
			<div id="rbgadmission" class="col-xs-3" onclick="admissionHoverOn()"><a href="#"><div class="rbgadmission hover"></div></a></div>
			<div id="rbgdirections" class="col-xs-3"><a href="{% link directions.html %}"><div class="rbgdirections hover"></div></a></div>
			<div id="rbgweather" class="col-xs-3"><a href="http://legacy.weather.weatherbug.com/weather-safety/online-weather-center/OnlineWeatherCenter.aspx?aid=4842" target="_blank"><div class="rbgweather hover"></div></a></div>
			
			<!-- Begin Page Down Code for Slides on Mobile -->
			<div id="page-down" class="col-xs-12">
				<center><span class="page-down-icon"><img src="/images/core/down-arrow.png" /></span></center>
				<!-- Code for Sprite Option -->
				<!-- <span class="page-down-icon" style="background-color:red;"><span class="jssora21l"></span></span> -->
			</div>
			<!-- End Page Down Code for Slides on Mobile -->
			
		</div>
		
	</div>

	</div>
	<!-- End Inner Info Div-->
</div>
</div>

<!-- Begin Outer Info Div -->

<div id="rbg-info-wrapper2">
	<div id="rbginfobg2">
	
		<div id="rbginfo" class="row">
			<div id="rbghours" class="col-sm-3">
					<b>GARDEN HOURS (MDT)</b>
					<div id="gardenHours2"></div>
					<div id="gardenStatus2"></div>
					<div id="otherNotes2"></div><br />
					<div>Only Service Animals are allowed in the garden</div><br />
						<a href="/general-info" style="text-decoration:none;color:#FFFFFF;font-size:12px">CLICK TO SEE ALL HOURS</a>
			</div>
			<div id="rbgadmission2" class="col-sm-3">
				
				{% include admission.html %}
				
			</div>
			<div id="rbgdirections" class="col-sm-3"><a href="/directions"><div class="rbgdirections"></div></a></div>
			<div id="rbgweather" class="col-sm-3"><a href="http://legacy.weather.weatherbug.com/weather-safety/online-weather-center/OnlineWeatherCenter.aspx?aid=4842" target="_blank"><div class="rbgweather"></div></a></div>
		</div>
	
	</div>
</div>

<!-- End Outer Info Div -->


    <!-- Marketing messaging and featurettes
    ================================================== -->
    <!-- Wrap the rest of the page in another container to center all the content. -->

<!-- Begin Content -->
<div id="rbghomebody" class="container-fluid">
  <div class="row">
  	  <div class="col-sm-12">
  	  
  	  {{ content }}
  	  
  	  </div>
  </div>
</div>

{% include footer.html %}

<!-- End Main Content -->

    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <script src="js/ie10-viewport-bug-workaround.js"></script>
    <script src="js/hours.js"></script>
    <script type="text/javascript" src="js/jssor.slider.mini.js"></script>
	{% include seasonal-css-js.html %}
	
	{% include jssor-slideshow-js.html %}    	
	
	
	
<!-- Google Analytics Code -->

{% include google-analytics.html %}

{% include dropdown-menu-behavior.html %}

{% include page-down.html %}
	
</body>
</html>
