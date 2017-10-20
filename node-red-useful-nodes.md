# Awesome List of Useful Node-RED Nodes
This is a list of nodes that you can add to the excellent Node-RED application. 
Node-RED is a flow-based application builder that minimises the need for coding.
One or mode nodes is added using a Node.JS/npm module. Once installed, the nodes can be added to a flow using
the Node-RED admin interface.

These nodes are ones that I either already use or think that I might find useful in the future or that 
I find awesome for some other reason. That's not to say that you would find them useful or even usable, this is only my opinion not a 
professional recommendation.

## Contents
<!-- TOC -->

- [Awesome List of Useful Node-RED Nodes](#awesome-list-of-useful-node-red-nodes)
    - [Contents](#contents)
        - [General](#general)
        - [Data Transformation](#data-transformation)
        - [User Interface Builders](#user-interface-builders)
    - [Node Development and Testing](#node-development-and-testing)
    - [Corrections and Contributions](#corrections-and-contributions)
    - [License](#license)

<!-- /TOC -->

### General
- [node-red-contrib-moment](https://github.com/TotallyInformation/node-red-contrib-moment) - Produces formatted Date/Time output using the Moment.JS library. Timezone, dst and locale aware.
  Input can be in any date/time format recognised by Moment.JS. Use to reformat dates and/or times, change timezones and do simple date/time arithmetic.

_[back to top](#contents)_

### Data Transformation
- Change node (builtin) - Allows multiple properties of an incoming msg to be transformed. 
  Includes the very powerful [JSONata](http://jsonata.org/) transform type
- [node-red-contrib-string](https://github.com/steveorevo/node-red-contrib-string) - Allows multiple string manipulations against a single msg property using [StringJS](http://stringjs.com/).

_[back to top](#contents)_

### User Interface Builders
Node-RED provides an administrative and editing interface for authoring flows but has no end-user interface by default. These nodes add the capacity to easily
build such an interface by creating web end-points.

- [Dashboard](https://github.com/node-red/node-red-dashboard) - A built-in set of nodes for quickly and easily creating a user interface with 2-way communication 
  between the users browser and the Node-RED server. Build around Angular v1. Very quick and easy to get going but the weight and complexity of Angluar and the limitations due to the interface to Node-RED limit the level of customisation you can achieve. Can only create a single end-point (url) but that end-point can be configured to multiple tabs.

- [UIBuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) - A single node that can be used to create many end points (urls, 1 per node instance). 
Provides an easy way to integrate any front-end library that can be installed via npm (e.g. Vue, [Riot](https://github.com/TotallyInformation/node-red-contrib-uibuilder/wiki/Example%3A-RiotJS), [Moon](https://github.com/TotallyInformation/node-red-contrib-uibuilder/wiki/Example%3A-MoonJS), Tachyons, ...). Provides a dedicated websockets channel for each end point with fallback to using long polling if websockets are not available (as in some secure enterprise environments).
Comes with an example set of template files that work out of the box. JQuery and Normalize.css libraries are pre-configured.

_[back to top](#contents)_

## Node Development and Testing
Nodes and other tools to help with the development and debugging of new nodes.

- [node-red-contrib-jktesting](https://github.com/TotallyInformation/node-red-contrib-jktesting) - Test nodes for Node-RED for learning and experimenting, 
  best practice, lots of hints and notes

_[back to top](#contents)_

## Corrections and Contributions
- Corrections are always gratefully received
- Please check for duplicates before suggesting a new contribution
- Either create a [pull request](https://github.com/TotallyInformation/awesome-to-me/pulls) or [raise an issue](https://github.com/TotallyInformation/awesome-to-me/issues)
- Keep descriptions short, simple and unbiased

Thanks for your help and support.

## License
[{{ site.github.license.name }}]({{ site.github.license.url }})

_[back to top](#contents)_
