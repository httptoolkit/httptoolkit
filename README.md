# HTTP Toolkit
[![100% Open-Source](https://img.shields.io/badge/Open--Source-100%25-%2330a237?style=flat-square&logo=opensourceinitiative&logoColor=%23fff)](https://github.com/httptoolkit/) [![Desktop downloads counter](https://img.shields.io/github/downloads/httptoolkit/httptoolkit-desktop/total?style=flat-square&color=%2330a237&label=Downloads)](https://github.com/httptoolkit/httptoolkit-desktop/releases/latest) [![GitHub Org's stars](https://img.shields.io/github/stars/httptoolkit?label=Org%20Stars&style=flat-square)](https://github.com/httptoolkit/) [![X (formerly Twitter) Follow](https://img.shields.io/badge/%40HttpToolkit-555?logo=x&style=flat-square)](https://twitter.com/httptoolkit/) [![Mastodon Follow](https://img.shields.io/mastodon/follow/000506268?domain=https%3A%2F%2Fmastodon.social&style=flat-square&logo=mastodon&logoColor=%23fff&label=Follow%20on%20Mastodon)](https://mastodon.social/@httptoolkit/) [![Funded by NLnet - NGI Zero Entrust](https://img.shields.io/badge/Funded%20by%20NLnet-NGI%20Zero%20Entrust-30a237?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNjcuNCAxNjguMiI%2BPHBhdGggZD0iTTEyNyA0NC45YzEuNC0xMS0xLjMtMjAuOC04LjEtMjkuNVMxMDMuMiAxLjcgOTIuMi40cy0yMC43IDEuMi0yOS40IDhBMzggMzggMCAwIDAgNDggMzIuNmwtLjQgMi41LS4yIDIuNWEzOS4zIDM5LjMgMCAwIDAgOC40IDI3QTM4IDM4IDAgMCAwIDgwIDc5LjNsMi40LjQgMS4zLjJhNDQgNDQgMCAwIDEgNS4yLTEyLjQgMzguMSAzOC4xIDAgMCAxLTQuNy0uMUg4NEEyNi41IDI2LjUgMCAwIDEgNjUuNyA1NyAyNi41IDI2LjUgMCAwIDEgNjAgNDJhMjcuOCAyNy44IDAgMCAxIC4yLTUuM3YtLjJjMS03LjUgNC40LTEzLjUgMTAuNC0xOC4xYTI2IDI2IDAgMCAxIDIwLjItNS42IDI2IDI2IDAgMCAxIDE4LjMgMTAuMyAyNyAyNyAwIDAgMSA0LjcgMjUuMWM0LjItMS4zIDguNi0yIDEzLjItMmwuMi0xLjN6bTUuMyA2LjYtMi41LS4zYTM5LjQgMzkuNCAwIDAgMC0yNyA4LjVBMzguNCAzOC40IDAgMCAwIDg4IDgzLjhjNC4zLjggOC4zIDIgMTIgMy45YTI2LjUgMjYuNSAwIDAgMSAxMC4zLTE4LjFjNC42LTMuNiA5LjYtNS42IDE1LTZhMjcuOCAyNy44IDAgMCAxIDUuNC4zaC4xYzcuNSAxIDEzLjUgNC40IDE4LjIgMTAuNGEyNiAyNiAwIDAgMSA1LjYgMjAuMiAyNy4zIDI3LjMgMCAwIDEtMzAuNSAyNGMuOSA0IDEuMSA4LjMuOCAxMi43IDEwIC42IDE5LTIuMiAyNy04LjVBMzguNiAzOC42IDAgMCAwIDE2NyA5Ni4xYzEuNC0xMS0xLjQtMjAuOC04LjItMjkuNS02LjMtOC0xNC4zLTEzLTI0LjEtMTQuN2wtMi41LS40ek0xMjkgNzguN2MtMy40LS40LTYuNS41LTkuMiAyLjZzLTQuMyA1LTQuNyA4LjNjLS41IDMuNS40IDYuNSAyLjUgOS4zczUgNC4zIDguNCA0LjdjMy40LjQgNi40LS40IDkuMi0yLjZzNC4zLTQuOSA0LjctOC4zYy40LTMuNC0uNC02LjUtMi42LTkuMnMtNC45LTQuMy04LjMtNC44em0tMTE2LTVjLjktNy42IDQuMy0xMy44IDEwLjMtMTguNCA2LTQuNyAxMi43LTYuNiAyMC4xLTUuNmE0NC4zIDQ0LjMgMCAwIDEtLjgtMTIuNyAzOCAzOCAwIDAgMC0yNyA4LjRDNi44IDUyLjIgMS44IDYxLjEuNSA3Mi4xczEuMyAyMC43IDguMSAyOS41YTM4IDM4IDAgMCAwIDI0LjIgMTQuN2wyLjQuNCAyLjUuMmM0LjYuMyA5LS4xIDEzLjItMS4zQTQxLjYgNDEuNiAwIDAgMCA3NSA5Ni44YTM4IDM4IDAgMCAwIDQuNC0xMi41Yy00LjMtLjctOC4zLTItMTItMy44YTI2LjUgMjYuNSAwIDAgMS0xMC4zIDE4LjEgMjYuNiAyNi42IDAgMCAxLTIwLjMgNS43aC0uMmMtNy40LTEtMTMuNS00LjUtMTguMS0xMC40LTQuNy02LTYuNi0xMi44LTUuNy0yMC4zek0zMi40IDY3YTEyIDEyIDAgMCAwLTQuOCA4LjQgMTIgMTIgMCAwIDAgMi42IDkuMSAxMiAxMiAwIDAgMCA4LjMgNC44IDEyLjUgMTIuNSAwIDAgMCAxNC0xMC45Yy40LTMuNC0uNC02LjUtMi42LTkuMmExMS45IDExLjkgMCAwIDAtOC4zLTQuN2MtMy41LS41LTYuNS40LTkuMiAyLjV6bTY0LjgtMzQuOGExMiAxMiAwIDAgMC04LjQtNC43Yy0zLjQtLjQtNi41LjQtOS4xIDIuNmExMS44IDExLjggMCAwIDAtNC44IDguM2MtLjQgMy40LjUgNi41IDIuNiA5LjIgMi4xIDIuNyA0LjkgNC4zIDguMyA0LjggMy40LjMgNi40LS41IDkuMi0yLjYgMi43LTIuMiA0LjMtNSA0LjctOC4zLjQtMy41LS40LTYuNi0yLjUtOS4zek04NSA4OC40bC0xLjMtLjFhNDIuMyA0Mi4zIDAgMCAxLTUuMSAxMi4zYzEuNSAwIDMuMSAwIDQuNy4yaC4yYTI2LjQgMjYuNCAwIDAgMSAxOC4zIDEwLjRjMy42IDQuNSA1LjUgOS41IDUuOCAxNWEyNy45IDI3LjkgMCAwIDEtLjIgNS4zdi4yYy0xIDcuNC00LjQgMTMuNS0xMC4zIDE4LjEtNiA0LjctMTIuOCA2LjUtMjAuMyA1LjZzLTEzLjYtNC40LTE4LjMtMTAuM2EyNi4zIDI2LjMgMCAwIDEtNC42LTI1LjJjLTQuMiAxLjQtOC42IDItMTMuMiAybC0uMiAxLjRhMzguNCAzOC40IDAgMCAwIDguMiAyOS40YzYuOCA4LjcgMTUuNyAxMy44IDI2LjYgMTUuMXMyMC43LTEuNCAyOS41LTguMmM4LTYuMyAxMy0xNC4zIDE0LjctMjQuMWwuNC0yLjUuMi0yLjRhMzkuNSAzOS41IDAgMCAwLTMyLjYtNDEuOGwtMi41LS40em01IDMyYTEyLjEgMTIuMSAwIDAgMC04LjQtNC43IDEyIDEyIDAgMCAwLTkuMSAyLjYgMTIuMSAxMi4xIDAgMCAwLTQuOCA4LjMgMTIgMTIgMCAwIDAgMi42IDkuMmMyLjEgMi44IDQuOSA0LjMgOC4zIDQuN2ExMi40IDEyLjQgMCAwIDAgMTMuOS0xMC45Yy40LTMuNC0uNC02LjQtMi41LTkuMnoiLz48L3N2Zz4%3D&labelColor=ffffff)](https://nlnet.nl/project/AppInterception/)


[HTTP Toolkit](https://httptoolkit.com/) is an open-source tool for debugging, testing and building with HTTP(S) on Windows, Linux & Mac.

You can use it to intercept, inspect & rewrite HTTP(S) traffic, from everything to anywhere. Explore Android app traffic, mock requests between your microservices, and x-ray your browser traffic to debug, understand and test anything.

---

<p align="center">
 :arrow_right: <strong>Find out more and try it out now at <a href="https://httptoolkit.com">httptoolkit.com</a></strong> :arrow_left:
</p>

<p align="center">
 Want to give feedback, report bugs, or get help? <a href="https://github.com/httptoolkit/httptoolkit/issues/new/choose">File an issue</a>.
</p>

<p align="center">
 Want to contribute to HTTP Toolkit's development yourself? <a href="https://github.com/httptoolkit/httptoolkit/#contributing-directly">Dive in</a>.
</p>

---

## Features

With HTTP Toolkit, you can:

* Instantly intercept browsers, most backend & scripting languages (from Node.js to PHP), Android devices, Electron apps and more with **one-click setup**.
* Collect interesting traffic without intercepting everything on your whole machine, so there's no extra noise and no side-effects - **just the traffic you care about**.
* Inspect the full headers & body for every request & response from every client, to immediately see what's really being sent & received on the wire.
* **Easily understand collected HTTP traffic**, with inline documentation for all standard headers & response statuses, plus body decoding, highlighting, folding, and other niceties, powered by the same internals as Visual Studio Code.
* Quickly find the data you care about, with exchanges highlighted by the type of client and tagged by category (images, JSON responses, errors), and free-text & structured filtering across all request & response data.
* Breakpoint live requests or responses, to **rewrite HTTP traffic on the fly**.
* **Mock endpoints or servers**, with flexible rule configurations to match and handle requests automatically, to send responses, inject failures & timeouts, or transparently redirect requests elsewhere.
* Intercept _any_ HTTP traffic: **HTTP Toolkit is a transparent HTTP proxy**, and can intercept plain HTTP, encrypted HTTPS, WebSockets, HTTP/2, proxy requests, direct requests, manually redirected packets, you name it, all on one port.

[![An HTTP Toolkit demo video](./demo.apng)](https://httptoolkit.com)

---

<p align="center">
 :arrow_right: Find out more and try it out now at <strong><a href="https://httptoolkit.com">httptoolkit.com</a></strong> :arrow_left:
</p>

---

## Send your feedback

HTTP Toolkit is driven by its community of users and their feedback. Have some ideas, problems or questions about HTTP Toolkit? **[Post an issue](https://github.com/httptoolkit/httptoolkit/issues/new/choose) in this repo**. If that's too public, you can also [send a message directly](https://httptoolkit.com/contact).

Would you like to help design the perfect HTTP debugging tool? Take a look through [the open issues](https://github.com/httptoolkit/httptoolkit/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc), and add a :+1: on topics you care about to prioritize them.

## Contributing directly

Want to go further, to build & contribute the HTTP Toolkit features & fixes you're looking for yourself? HTTP Toolkit is 100% open source, so you can help shape it directly! **All contributors get free HTTP Toolkit Pro** (more background on this [over here](https://httptoolkit.com/blog/free-as-in-beer)).

That includes code contributions, but documentation improvements, article & blog posts elsewhere about the project, bug & security reports, and anything else that helps drive HTTP Toolkit forwards. The goal is to reward anything that helps drive HTTP Toolkit development or bring it to new people. To claim your Pro account, [get in touch](https://httptoolkit.com/contact) once you've made your contribution, with the email you'd like associated with your account. Feel free to get in touch with any other questions about this too.

### Where to start

This [github organization](https://github.com/httptoolkit) contains the entire project.

Yes, even the account management servers, even the paid features, _everything_. All of that is open source, licensed as a mixture of copyleft AGPL (for the HTTP Toolkit-specific components, ensuring all direct derivative projects are open-source too) and permissive Apache-2/MIT licenses (for all the general-purpose reusable libraries).

The main repos you might be interested in are:

* [HTTP Toolkit Website](https://github.com/httptoolkit/httptoolkit-website) - the source for [the website](https://httptoolkit.com), including the marketing pages, the blog, and the docs.
* [HTTP Toolkit UI](https://github.com/httptoolkit/httptoolkit-ui) - the core of the product, a TypeScript + React app that powers most of the functionality you use, except for things that can't be done in a web page (i.e. starting a proxy, and setting up client interception).
* [HTTP Toolkit Server](https://github.com/httptoolkit/httptoolkit-server) - the backend of the product, a TypeScript + node.js server that does the things the UI can't do: starting a proxy, and setting up client interception.
* [Mockttp](https://github.com/httptoolkit/mockttp) - the HTTP(S) proxy itself, and all low-level logic around that, as a standalone TypeScript library. Used in HTTP Toolkit for traffic interception, but also usable standalone as a testing tool, or as a programmatically controllable intercepting HTTP(S) proxy.
* [HTTP Toolkit for Android](https://github.com/httptoolkit/httptoolkit-android) - the Android app, a native Kotlin + Java app that manages certificate trust & enforces HTTP interception on Android devices.
* [HTTP Toolkit Desktop](https://github.com/httptoolkit/httptoolkit-desktop) - a TypeScript + Electron wrapper, which combines the UI & the server and builds convenient per-platform installers.

Each repo has its own readme explaining how to get set up and outlining how the component works. Check out the issues in this repo for ideas, feel free to [ask questions](https://httptoolkit.com/contact), and dive in!
