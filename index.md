---
layout: home
title: Home
landing-title: Wild Cards Shufflers
description: 
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
			<img style="display:block;" width="30%" height="30%" src="jestLogo.jpg" alt="" align = "right" />
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Get Started</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>About</h2>
		</header>
		<ul class="actions">
			<li><a href="landing.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>

