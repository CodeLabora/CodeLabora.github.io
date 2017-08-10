<head>
  <meta charset="UTF-8">
  <title>{% if page.title %}{{ page.title }} | CodeLabora{% endif %}</title>
  <meta name="description" content="{{ page.description | default: site.description | default: site.github.project_tagline }}"/>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="theme-color" content="#155799">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
  <link rel="stylesheet" href="{{ '/assets/css/main.css' }}">
  <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">

  <link rel="shortcut icon" type="image/x-icon" href="favicon.ico?">
</head>
