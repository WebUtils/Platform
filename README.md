# WebUtils Platform

The WebUtils Platform is a set of web resources and utilities to enable faster mobile web app development, and the nexus of activity around WebUtils apps.

## What is WebUtils?

WebUtils is a project to make great apps for the mobile web. Browsers on mobile devices are up to it, so let's get busy!

## Request an app!

Use the Github Issues on the Platform project ([here](https://github.com/WebUtils/Platform/issues)) to request new apps. Please provide some content to your suggestion, so it can form the basis of a spec if your idea is picked up! Please also prefix the title with "Request: " and tag it "request-app" so we can find it more easily.

## Build your own app

You don't need to use the WebUtils platform to build your own app. But it's cool if you do! We're here as a helping hand to kick-start things a bit. If you prefer to do something different then do so by all means. [Leave a note on the wiki](https://github.com/WebUtils/Platform/wiki) to let us know you have built something cool!

There is a "quickstart" directory in this project you can use as a template, if you wish. If you would like to use Bootstrap too, then I have previously used [this cut-down configuration](http://getbootstrap.com/customize/?id=254290f9e9656ac38c73) to help with things like buttons and other common reusable components. 

## Philisophy

The web platform is [browser features + APIs](http://chris-alexander.co.uk/on-engineering/this-is-also-the-web-platform/). This means leveraging all kinds of browser-based functionality, enhanced with the power of APIs.

This doesn't mean (necessarily) making your own APIs. For the majority of simple use cases, provisioning your own infrastructure/containers (and then having to pay for it) is an unnecessary burden, a barrier to entry, and a cost that would have to be balanced with in-app purchases, ads and the like. Some of the world's biggest internet companies offer APIs which can do all kinds of things (and with enough creativity, can solve a whole lot of problems just on their own); [Google](https://developers.google.com/), [Facebook](https://developers.facebook.com/) and [Github](https://developer.github.com/) come to mind.

We're here to build open web apps that don't need specific code to run on specific devices - why would we then build specific APIs for them?

Here are some more specific principles I will apply to WebUtils apps:

* No compiling. We're moving away from this app-based world and browser technologies are more than capable of running without requiring a compiler to build JS or CSS for you. *Exception: using Jekyll to do basic HTML templating.*
* Build for the edge. Prove what's possible and let the slow browser manufacturers catch up.
* Use other people's APIs over building your own.
* Contribute to open-source where possible.

(We're still working through what we're going to do for offline support, as this is a bit of a half-way house in the browser world at the moment. But look out for updated guidance coming soon!)

Feel free to disregard any or all of the above. The web is everyone's, after all :-)

## Protips

* Use [Github Pages](https://pages.github.com/) to host your app's static site. It's free and awesome.
* [CDN first](https://developers.google.com/speed/libraries/), ask questions later.
* [Atom](https://atom.io/) is pretty cool, even on Windows.
