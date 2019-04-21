---
layout: default
---

{% assign post = page %}

<!-- <style>
	$secondary-color: #000;
	body {
  		color: #000;
  		background-color: #fff;
	}
	.topnav {
  		background-color: #fff;
  		color: #000;
	}
	.topnav a {
	  color: #000;
	}
	.logo {
	  background-color: #fff;
	}
	.post-meta {
	    color: #000;
	}
</style> -->

{% include post-metadata.html %}

{{ content }}