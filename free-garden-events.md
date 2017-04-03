---
title: Free Garden Events
layout: default
---

<span class="eventdivide">
	<hr>
		<div class="grid-header">FREE GARDEN EVENTS</div>		
	<hr>
</span>

<br />



	<br />
	
	<center><img class="text-center responsive" alt="" src="/images/zap-color.jpg" style="max-width:350px;"/></center>
	<br />
	<h4 class="text-center">Thanks to funding in part by Salt Lake County Zoo, Arts, and Parks Program (ZAP), guests can enjoy six days of free Garden admission.</h4>

	<br />
	
	<div class="col xs-12">
		<h3>ZAP FREE DAYS</h3>		
		<hr>
		<br />
		
		<h4 class="green">Arbor Day - The last Friday of every April </h4>
		<h5>April 29, 2016</h5>
		<h6>Activities 9AM-3PM</h6>
		<p>Join us for a fun day of activities and interactive exploration stations throughout the Garden. Due to the generous support of Rocky Mountain Power, all guests leave with a free tree to take home (while supplies last).</p>
		
		<br />
		
		<h4 class="green">Pioneer Day</h4>
		<h5>Every July 24</h5>
		<h6></h6>
		<p>Spend time with family and friends on the holiday at Red Butte Garden with free admission all day long.</p>
		
		<br />
		
		<h4 class="green">Labor Day - The first Monday of every September</h4>
		<h5>Monday, September 5, 2016 </h5>
		<h6></h6>
		<p>On this day we especially acknowledge the volunteers who labor in the Garden and at events to help make your Garden visit a wonderful experience.</p>
		
		<br />
		
		<h4 class="green">Zeke Dumke, Jr. Day - The first Monday of every October</h4>
		<h5>Monday, October 3, 2016</h5>
		<h6></h6>
		<p>In recognition of his visionary role in the founding and development of Red Butte Garden, the first Monday of every October is now "Ezekiel R. Dumke, Jr. Free Day."</p>	
		
		<br />
		
		<h4 class="green">Annual Holiday Open House & Art Fair</h4>
		<h5>Saturday & Sunday, December 3 & 4, 2016</h5>
		<h6></h6>
		<p>Held the first weekend of every December, the Holiday Open House has become a wonderful tradition at the Garden. For two days we have free Garden admission to the public and fantastic local artists offering their work for sale. Every year we attract holiday shoppers looking for special, unique gifts and guests who explore the winter garden.</p>
	
		<br />
	
	</div>
	
	<div class="col xs-12">
		<h3>FREE EVENTS AT RED BUTTE GARDEN</h3>		
		<hr>
		
		<!--
		<ul>
			<li><a href="/sundance">Sundance Institute Summer Film Series</a></li><br />
			<li><a href="/horticulture-lecture-series">Horticulture Spotlight Lecture Series</a></li><br />
			<li><a href="/spyhop-heatwave">SPYHOP Heatwave Festival - July 18, 2016</a></li><br />
		</ul>
		-->
		{% for post in site.categories.free %}
		    {% if post.url %}        
			<div class="col-sm-4">
				<a href="{{ post.url }}">
				<div class="eventwrapsmall hover">
				
					<img src="../images/events/{{ post.event-image }}">
					
					<div class="eventinfo">
						<div class="eventname">{{ post.title }}</div>
						<div class="eventdate">{{ post.event-dates }}</div>
						<div class="eventnotes">{{ post.event-notes}}</div>
					</div>
			
				</div>
				</a> 
			</div>
		    {% endif %} 
		{% endfor %}
  
  	</div>
  	
  	<br />
	


