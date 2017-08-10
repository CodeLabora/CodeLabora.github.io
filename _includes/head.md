<head>
  <meta charset="UTF-8">
  <title>{% if page.title %}{{ page.title }} | CodeLabora{% endif %}</title>
  <meta name="description" content="{{ page.description | default: site.description | default: site.github.project_tagline }}"/>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="theme-color" content="#155799">
  <link rel="stylesheet" href="{{ '/assets/css/main.css' }}">
  <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
  <link rel="shortcut icon" type="image/x-icon" href="favicon.ico?">
  <meta itemprop="email" content="codelabora@gmail.com">
</head>
