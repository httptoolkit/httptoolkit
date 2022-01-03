# HTTP Toolkit
[![Follow @httptoolkit on Twitter](https://img.shields.io/twitter/follow/httptoolkit?color=%234c1&style=flat-square)](https://twitter.com/httptoolkit) [![GitHub Org's stars](https://img.shields.io/github/stars/httptoolkit?label=org%20stars&style=flat-square)](https://github.com/httptoolkit/) [![Desktop downloads counter](https://img.shields.io/github/downloads/httptoolkit/httptoolkit-desktop/total?style=flat-square)](https://github.com/httptoolkit/httptoolkit-desktop/releases/latest) [![Open feature suggestions](https://img.shields.io/github/issues/httptoolkit/httptoolkit?label=feature%20suggestions&style=flat-square)](https://github.com/httptoolkit/httptoolkit/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc) ![100% open-source](https://img.shields.io/badge/open--source-100%25-%23999?style=flat-square)

[HTTP Toolkit](https://httptoolkit.tech) is an open-source tool for debugging, testing and building with HTTP(S) on Windows, Linux & Mac.

You can use it to intercept, inspect & rewrite HTTP(S) traffic, from everything to anywhere. Explore Android app traffic, mock requests between your microservices, and x-ray your browser traffic to debug, understand and test anything.

---

<p align="center">
 :arrow_right: <strong>Find out more and try it out now at <a href="https://httptoolkit.tech">httptoolkit.tech</a></strong> :arrow_left:
</p>

<p align="center">
 <em>Want to give feedback, or get help? <a href="https://github.com/httptoolkit/httptoolkit/issues/new">File an issue</a>.</em>
</p>

<p align="center">
 <em>Want to contribute to HTTP Toolkit's development yourself? <a href="https://github.com/httptoolkit/httptoolkit/#contributing-directly">Dive in</a>.</em>
</p>

---

## Features

With HTTP Toolkit, you can:

* Instantly intercept browsers, most backend & scripting languages (from Node.js to PHP), Android devices, Electron apps and more with **one-click setup**.
* Collect interesting traffic without intercepting everything on your whole machine, so there's no extra noise and no side-effects - **just the traffic you care about**.
* Inspect the full headers & body for every request & response from every client, to immediately see what's really being sent & received on the wire.
* **Easily understand collected HTTP traffic**, with inline documentation for all standard headers & responses statuses, plus body decoding, highlighting, folding, and other niceties, powered by the same internals as Visual Studio Code.
* Quickly find the data you care about, with exchanges highlighted by client and tagged by category (images, JSON responses, errors), and free-text search across all request & response metadata.
* Breakpoint live requests or responses, to **rewrite HTTP traffic on the fly**.
* **Mock endpoints or servers**, with a flexible rule configurations to match and handle requests automatically, to send responses, inject failures & timeouts, or transparently redirect requests elsewhere.
* Intercept _any_ HTTP traffic: **HTTP Toolkit is a transparent HTTP proxy**, and can intercept plain HTTP, encrypted HTTP(S), HTTP/2, proxy requests, direct requests, manually redirected packets, you name it, all on one port.

[![An HTTP Toolkit demo video](./demo.apng)](https://httptoolkit.tech)

---

<p align="center">
 :arrow_right: Find out more and try it out now at <strong><a href="https://httptoolkit.tech">httptoolkit.tech</a></strong> :arrow_left:
</p>

---

## Send your feedback

HTTP Toolkit is driven by its community of users and their feedback. Have some ideas, problems or questions about HTTP Toolkit? **[Post an issue](https://github.com/httptoolkit/httptoolkit/issues/new) in this repo**. If that's too public, you can also [send a message directly](https://httptoolkit.tech/contact).

Would you like to help design the perfect HTTP debugging tool? Take a look through [the open issues](https://github.com/httptoolkit/httptoolkit/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc), and add a :+1: on topics you care about to prioritize them.

## Contributing directly

Want to go further, to build & contribute the HTTP Toolkit features & fixes you're looking for yourself? HTTP Toolkit is 100% open source, so you can help shape it directly! **All contributors get free HTTP Toolkit Pro** (more background on this [over here](https://httptoolkit.tech/blog/free-as-in-beer)).

That includes code contributions, but documentation improvements, article & blog posts elsewhere about the project, bug & security reports, and anything else that helps drive HTTP Toolkit forwards. The goal is to reward anything that helps drive HTTP Toolkit development or bring it to new people. To claim your Pro account, [get in touch](https://httptoolkit.tech/contact) once you've made your contribution, with the email you'd like associated with your account. Feel free to get in touch with any other questions about this too.

### Where to start

This [github organization](https://github.com/httptoolkit) contains the entire project.

Yes, even the account management servers, even the paid features, _everything_. All of that is open source, licensed as a mixture of copyleft AGPL (for the HTTP Toolkit-specific components, ensuring all direct derivative projects are open-source too) and permissive Apache-2/MIT licenses (for all the general-purpose reusable libraries).

The main repos you might be interested in are:

* [httptoolkit.tech](https://github.com/httptoolkit/httptoolkit.tech) - the [HTTP Toolkit website](https://httptoolkit.tech), including the marketing pages, the blog, and the docs.
* [HTTP Toolkit UI](https://github.com/httptoolkit/httptoolkit-ui) - the core of the product, a TypeScript + React app that powers most of the functionality you use, except for things that can't be done in a web page (i.e. starting a proxy, and setting up client interception).
* [HTTP Toolkit Server](https://github.com/httptoolkit/httptoolkit-server) - the backend of the product, a TypeScript + node.js server that does the things the UI can't do: starting a proxy, and setting up client interception.
* [Mockttp](https://github.com/httptoolkit/mockttp) - the HTTP(S) proxy itself, and all low-level logic around that, as a standalone TypeScript library. Used in HTTP Toolkit for traffic interception, but also usable standalone as a testing tool, or as a programmatically controllable intercepting HTTP(S) proxy.
* [HTTP Toolkit for Android](https://github.com/httptoolkit/httptoolkit-android) - the Android app, a native Kotlin + Java app that manages certificate trust & enforces HTTP interception on Android devices.
* [HTTP Toolkit Desktop](https://github.com/httptoolkit/httptoolkit-desktop) - a TypeScript + Electron wrapper, which combines the UI & the server and builds convenient per-platform installers.

Each repo has its own readme explaining how to get set up and outlining how the component works. Check out the issues in this repo for ideas, feel free to [ask questions](https://httptoolkit.tech/contact), and dive in!
