## Synopsis

VUI - Voice User Interface

If you've built Amazon Alexa skills using NodeJS then you've likely come across a handly set of tools for locally developing Alexa Skills that can be deployed to the cloud ([Alexa App](https://github.com/alexa-js/alexa-app) and [Alexa App Server](https://github.com/alexa-js/alexa-app-server)). These tools are great and make building, testing, and deploying Alexa skills simple.


## Motivation

With Cortana Skills coming out I was hoping to just be able to re-use these tools for Cortana Skill development too; out of the box. But sadly there were a many caveats. But after modifying the [alexa-app](https://github.com/alexa-js/alexa-app) code, what this repo is built off of, I eventually was able to build, test, and deploy Cortana skills using the [Alexa App Server](https://github.com/alexa-js/alexa-app-server) and this modified alexa-app which I'm calling [Vui App](https://github.com/user1m/vui-app). [Vui App](https://github.com/user1m/vui-app) is a cross platform sdk for building Alexa AND Cortana skills using the [Alexa App Server](https://github.com/alexa-js/alexa-app-server).


## Installation

`npm install git://github.com/user1m/vui-app.git`
`npm i`


## Acknowledgements
* **[Matt Kruse](https://github.com/alexa-js/alexa-app)**

Most of this repo is a clone of [alexa-app](https://github.com/alexa-js/alexa-app) with necessary modifications to make it cross-plaform for building both Alexa AND Cortana Skills.

## License

[License (MIT)](https://github.com/alexa-js/vui-app/master/LICENSE.md)
