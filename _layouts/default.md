---

---

{% include head.html %}

<body>
	<div class="logo">
		<h1>{{ site.title }}</h1>
	</div>

	<div class="topnav">
	  <a href="/">[0] home</a>
	  <a href="/archives/">[1] archives</a>
	  <a href="/about/">[2] about</a>
	</div>

	<div class="wrapper">
		<h1>{{ page.title | downcase }}</h1>
		{{ content }}
	</div>



</body>