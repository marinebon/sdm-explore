# sdm-explore
Explore species distribution modeling

## html

These web pages (\*.html) are typically rendered from Quarto markdown (\*.qmd):

<!-- Jekyll rendering -->
{% for file in site.static_files %}
  {% if file.extname == '.html' %}
* [{{ file.basename }}]({{ site.baseurl }}{{ file.path }})
  {% endif %}
{% endfor %}

## source

See [github.com/marinebon/sdm-explore](https://github.com/marinebon/sdm-explore)
