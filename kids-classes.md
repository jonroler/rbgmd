---
title: Kids Classes | Red Butte Garden
layout: default
---

<div class="row-fluid clearfix">
	<div class=" col-xs-12 eventdivide">
			<hr>
				<div class="grid-header">KIDS CLASSES</div>		
			<hr>
	</div>
</div>

<div class="row-fluid">

  {% for post in site.categories.kid-class %}
    {% if post.url %}        
	<div class="col-xs-12 col-sm-6 col-md-4 col-lg-4">
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