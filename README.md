# Awesome To Me
Awesome style lists of things useful or interesting to me. Also awesome lists of things to avoid &amp; why.

To best view these lists, please use the [Github Pages version](https://totallyinformation.github.io/awesome-to-me/).

## List of Lists
- [Awesome List of Node.js Backend Modules](nodejs-backend-modules.md)
- [Node.js Backend Modules to Avoid](nodejs-backend-avoid.md)

### Corrections and Contributions
- Corrections are always gratefully recieved
- Please check for duplicates before suggesting a new contribution
- Either create a [pull request](https://github.com/TotallyInformation/awesome-to-me/pulls) or [raise an issue](https://github.com/TotallyInformation/awesome-to-me/issues)
- Keep descriptions short, simple and unbiased

Thanks for your help and support.

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
