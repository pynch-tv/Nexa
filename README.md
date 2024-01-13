# Nexa OpenAPI
A RESTful API to EVS Audio Video Servers.
![Untitled](https://github.com/pynch-tv/Nexa/assets/4082369/706e5937-f695-43aa-a806-421ad1c345d0)

HTTP and the web have become the lingua-franca in the ICT world and have found their entry in the broadcast world as well. But not all machines in the broadcast world (old and new) want to expose such an HTTP interface to the outside world: not part of the offering, not to make it easy to interface with and stay within the product family (vendor lock-in).

With Nexa we want to provide an HTTP RESTful API on top of existing audio video production servers - made for the broadcast integrators and programmers.

## Design Philosophy

We want to API to be instant recognizable by programmers and broadcast engineers! How? By applying all the industry best-practices and API guidelines put forward by industry: [W3C](https://www.w3.org/TR/dwbp/), [IETF](https://ietf.org), [OGC](https://ogcapi.ogc.org/), [industry best practices](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/) and [government API Design Rules](https://gitdocumentatie.logius.nl/publicatie/api/adr/).

By following the well-known API patterns, developers can get their first successful call within minutes [TTFC](https://nordicapis.com/why-time-to-first-call-is-a-vital-api-metric) (The time taken between a developer accessing documentation, and/or signing up for an API key and making their first successful API call (of any complexity)). Additionally, by following the best practices, AI coding assistants (eg [GitHub's Co-Pilot](https://github.com/features/copilot)) can predict code more easely and accuratly.

## API for machines and humans

Nexa can render the same information in 2 ways: as [JSON](https://www.w3schools.com/whatis/whatis_json.asp) (for machine consumption) and in [HTML](https://www.w3schools.com/html/html_intro.asp) (for human consumption).

A side-by-side comparison between HTML and JSON respectively:

![Screenshot 2024-01-13 110321](https://github.com/pynch-tv/Nexa/assets/4082369/9881eea4-7527-44ab-838c-526b91a8b9f2)

The one on the left (HTML) is called with http://localhost:8080/acme/unit11/v1/ and the one on the right (JSON) with http://localhost:8080/acme/unit11/v1/?f=json (see the difference?).

## Installation

Nexa comes as an offline installer (that makes it slightly larger) that does not require an internet connection. Typically production server are not exposed to the internet, for security (and other) reasons. The installer is self contained and will only install what is really needed. The installer does not mess with the Windows Registry, nor with any other settings that might affect the behaviour of running applications.

Nexa must be installed in the network that is used by the servers. More on the installation process [here](https://github.com/pynch-tv/Nexa/wiki).
