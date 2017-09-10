# Awesome To Me
Awesome style lists of things useful or interesting to me. Also awesome lists of things to avoid &amp; why.

To best view these lists, please use the [Github Pages version](https://totallyinformation.github.io/awesome-to-me/).

## My Lists of Awesome
- [Node.js Backend Modules](nodejs-backend-modules.md)
- [Windows Applications](windows-apps.md)

## My Avoid Lists
- [Web/Cloud Services to **Avoid**](web-avoid.md)
- [Node.js Backend Modules to **Avoid**](nodejs-backend-avoid.md)
- [Windows Applications to **Avoid**](windows-avoid.md)

## Other People's Lists
Check my lists for additional lists. These are ones that don't (yet) fit into my own but I want to keep to hand for future use.
- [Awesome Self-Hosted](https://github.com/Kickball/awesome-selfhosted) - 
  A list of Free Software network services and web applications which can be hosted locally.

  Includes email, web serevrs, Groupware, IM and much more.
  
- [Awesome Bots](https://github.com/BotCube/awesome-bots) - Lots of resources related to Bots.

- [Awesome Electronics](https://github.com/monostable/awesome-electronics) - 
  Mainly resources for simulators, board design, forums, parts search.

## Corrections and Contributions
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
