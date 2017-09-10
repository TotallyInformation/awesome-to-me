# Awesome To Me
Awesome style lists of things useful or interesting to me. Also awesome lists of things to avoid &amp; why.

## List of Lists

## License
These lists and pages are all licenced with the [{{ site.github.license.name }}]({{ site.github.license.url }}).

## Totally Information
{% for orgmember in site.github.organization_members %}
  * [{{ orgmember.login }}]({{ orgmember.html_url }})
{% endfor %}

## Totally Information's Github Repositories
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
