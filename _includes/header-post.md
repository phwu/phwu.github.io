<head><link rel="stylesheet" type="text/css" href="{{ site.url }}/css/style.css"></head>
<ul>
          {% for page in site.html_pages %}
            <li>
              <a href="{{ page.url }}">{{ page.title }}</a>
            </li>
          {% endfor %}
</ul>

{{ page.title }}
===================