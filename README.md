# Use The Platform

> Front-end frameworks like Angular, React, and Ember are popular for building web apps, but are they essential? We'll look at how leveraging native browser capabilities with decoupled tools can provide long-term flexibility and maintenance.

This was a talk given at the 2017 Des Moines Web Geeks Social Event.

The presentation can be viewed at [eheikes.github.io/use-the-platform-talk](http://eheikes.github.io/use-the-platform-talk/), or from the [`dist` folder](dist/) in this repository.

## Local Build

The presentation can be built and served locally using [Node.js](https://nodejs.org/). To begin, `git clone` this repository and then run `npm install` at the command line (in the new folder).

The npm tasks are:

* `npm run clean` -- Deletes the `dist` folder
* `npm run build` -- Compiles the presentation into the `dist` folder (you'll need [dos2unix](http://linuxcommand.org/man_pages/dos2unix1.html) on your machine)
* `npm start` -- Starts a local server to serve the presentation
* `npm run deploy` -- Deploys the presentation to the Github Page
