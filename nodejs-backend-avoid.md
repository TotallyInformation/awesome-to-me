# Node.js Backend Modules to Avoid
This is a list of backend (server-side) Node.js modules that I will personally be avoiding! 
That's not to say that you might not find them useful or usable, 
this is only my opinion not a professional recommendation.

They show serious flaws of some kind. Perhaps being unstable, are insecure or maybe even just backed by dodgy morals.

## Contents
- [Node.js Backend Modules to Avoid](#nodejs-backend-modules-to-avoid)
  - [Servers](#servers)
  - [Frameworks](#frameworks)
- [Contributing](#corrections-and-contributions)
- [License](#license)

### Servers
Complete servers ready to use.

### Frameworks
Complex modules that can be used to build systems and services
- [Cote](http://cote.js.org) - 
  *"A Node.js library for building zero-configuration microservices." 
  "cote lets you write zero-configuration microservices in Node.js 
  without nginx, haproxy, redis, rabbitmq or anything else. It is batteries — and chargers! — included."*
  
  At first glance seems like a really nice tool. However, there is basically **no security** at all 
  and the authors [don't seem to understand why that might be an issue](https://github.com/dashersw/cote/issues/53)!
  
  I'll be avoiding this one thanks, there are enough securty problems around, I don't want to add to them. 
  Last checked 2017-09-10

## Corrections and Contributions
- Corrections are always gratefully recieved
- Please check for duplicates before suggesting a new contribution
- Either create a [pull request](https://github.com/TotallyInformation/awesome-to-me/pulls) 
  or [raise an issue](https://github.com/TotallyInformation/awesome-to-me/issues)
- Keep descriptions short, simple and unbiased

Thanks for your help and support.

## License
[{{ site.github.license.name }}]({{ site.github.license.url }})
