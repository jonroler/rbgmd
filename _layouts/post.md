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
    
    <!-- Begin ShareThis Social Media Code -->
    
	<script type="text/javascript">var switchTo5x=true;</script>
	<script type="text/javascript" id="st_insights_js" src="https://ws.sharethis.com/button/buttons.js?publisher=d5e6f2de-74fd-427e-8fc7-c9d235a7c905"></script>
	<script type="text/javascript">stLight.options({publisher: "d5e6f2de-74fd-427e-8fc7-c9d235a7c905", doNotHash: false, doNotCopy: false, hashAddressBar: false});</script>
	
	<!-- Script that disabled hover effect for ShareThis code -->
	<script type="text/javascript">stLight.options({publisher:'d5e6f2de-74fd-427e-8fc7-c9d235a7c905',onhover: false});
	
	</script>
    
    <!-- End ShareThis Social Media Code -->
    
<title>{{ page.title }}</title>
    
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  {% include favicon.html %}  
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Open+Sans" /> <!-- Font 'Open Sans' Hosted by Google -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="/CSS/summer.css?v=1"> <!-- Additional local CSS -->
  
{% include searchbar-toggle.html %}
  
</head>
<body>
{% include navbar.html %}

<div id="rbgdefaultbody" class="container-fluid">
  <div class="row">
  	  <div class="col-sm-12">
  	  
  	  	<!-- <div class="container-fluid"> -->
  	  	<div class="rbgbanner"><img src="/images/banners/{{ page.blog-banner }}"></div>
  	  	
  	  	<br />
  	  	
        <h2>{{ page.title }}</h2>
        <h5>Submitted {{ page.post-date }} at {{ page.post-time }} </h5>
  	  	
        <br />
        {{ content }}
  	  	</div>
  	  	
  	  	<br />
		
  	  	<!-- </div> -->
  </div>
</div>

<!-- Go to www.addthis.com/dashboard to customize your tools --> <script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-5873c57d776e261e"></script> 

<!-- Google Analytics Code -->

{% include google-analytics.html %}

</body>
{% include footer.html %}
{% include seasonal-css-js.html %}