---

---

{% include head.html %}

<body>
	{% include header.html %}

	{% include nav.html %}

	<div class="wrapper">
		<h1>{{ page.title | downcase }}</h1>
		{{ content }}
	</div>

	{% include footer.html %}


</body>