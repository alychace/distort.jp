---

---

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width initial-scale=1" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <link href="https://fonts.googleapis.com/css?family=PT+Sans:400,400i,700,700i|PT+Serif:400,400i,700,700i" rel="stylesheet">

  <title>{% if page.title and page.url != "/" %}{{ page.title }} | {% endif %}{{ site.title }}</title>
  <meta name="description" content="{{ page.description }}">

  <link rel="shortcut icon" href="{{ '/assets/img/favicon.ico' | prepend: site.baseurl | prepend: site.url }}">

  <link rel="stylesheet" href="{{ '/assets/css/main.css' | prepend: site.baseurl | prepend: site.url }}">
  <link rel="canonical" href="{{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url }}">
</head>

<body>
	<div class="logo">
		<h1>{{ site.title }}</h1>
	</div>

	<div class="topnav">
	  <a href="/">home</a>
	  <a href="/archives/">archives</a>
	  <a href="/about/">about</a>
	</div>

	<div class="wrapper">
		<h1>{{ page.title | downcase }}</h1>
		{{ content }}
	</div>



</body>