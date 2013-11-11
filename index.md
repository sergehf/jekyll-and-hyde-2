---

layout: default
title: Home

---
<div class="boxes">
<div class="box">
	<div class="boxContent">
		<h2>A little about myself...</h2>
		<br>
		I've been living in Los Angeles for pretty much my whole life. Just like everyone else, I say I hate it, but honestly, I don't think I could live anywhere else! <br>
		<br>
		I'm a diehard LA sports fan, except the Clippers, and the Angels, but the Angels aren't even from LA so I guess that doesn't count. I try to catch as many Lakers/Dodgers/Kings games as possible. <br>
	</div>
	<div class="button"><a href=" {{site.url}}/about/">More</a></div>
</div>

<div class="box">
	<div class="boxContent">
		<h2>What I like to do...</h2>
		<br>
		I love coding - specifically html, css, and jquery. I enjoy seeing designs come to life and take pride in building those designs out the right way. <br>
		<br>
		Besides developing, I enjoy going to new restaurants, exploring various bars, and discovering local places that I never knew existed.
	</div>
	<div class="button"><a href=" {{site.url}}/projects/">More</a></div>
</div>

<div class="box">
	<div class="boxContent">
		<h2>My recent thoughts...</h2>
		<br>
		{% for post in site.posts limit: 1 %}
	    	<h3><a href=" {{ post.url }} "><strong> {{ post.title }} </strong></a></h3><br>
	    	{{ post.excerpt }}
	    	<div class="button"><a href="{{ post.url }}">More</a></div> <br>
	  	{% endfor %}
  	</div>
  	<div class="button"><a href=" {{site.url}}/blog/">Blog</a></div>
</div>
</div>

<div class="clear"></div>


