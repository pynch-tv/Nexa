# Nexa OpenAPI

Automate your AudioVideo servers through a unified API

![Untitled](https://github.com/pynch-tv/Nexa/assets/4082369/706e5937-f695-43aa-a806-421ad1c345d0)

Nexa provides an HTTP RESTful OpenAPI on top of existing audio video production servers - made for the broadcast integrators and programmers.

## OpenAPI

We want the API to be instantly recognizable by programmers and broadcast engineers! How? By applying all the industry best-practices and API guidelines put forward by industry: [W3C](https://www.w3.org/TR/dwbp/), [IETF](https://ietf.org), [OGC](https://ogcapi.ogc.org/), [industry best practices](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/) and [government API Design Rules](https://gitdocumentatie.logius.nl/publicatie/api/adr/).

By following the well-known API patterns, developers can get their first successful call within minutes [TTFC](https://nordicapis.com/why-time-to-first-call-is-a-vital-api-metric) (The time taken between a developer accessing documentation, and/or signing up for an API key and making their first successful API call (of any complexity)). Additionally, by following the best practices, AI coding assistants (eg [GitHub's Co-Pilot](https://github.com/features/copilot)) can predict code more easely and accuratly.

<img width="1430" alt="Screenshot 2024-06-05 at 11 46 12" src="https://github.com/pynch-tv/Nexa/assets/4082369/8cb0cf8d-43e7-45a6-8f8c-143bec11d084">

## API for machines and humans

Nexa can render the same information in 2 ways: as [JSON](https://www.w3schools.com/whatis/whatis_json.asp) (for machine consumption) and in [HTML](https://www.w3schools.com/html/html_intro.asp) (for human consumption).

A side-by-side comparison between HTML and JSON respectively:

![296444185-9881eea4-7527-44ab-838c-526b91a8b9f2](https://github.com/pynch-tv/Nexa/assets/4082369/5881eb47-6dcc-4ab0-9f52-0173636c300a)

The one on the left (HTML) is called with http://localhost:8080/acme/unit11/v1/ and the one on the right (JSON) with http://localhost:8080/acme/unit11/v1/?f=json (see the difference?).

## Installation

Nexa comes as an offline installer (that makes it slightly larger) that does not require an internet connection. Typically production server are not exposed to the internet, for security (and other) reasons. The installer is self contained and will only install what is really needed. The installer does not mess with the Windows Registry, nor with any other settings that might affect the behaviour of running applications.

Nexa must be installed in the network that is used by the servers. More on the installation process [here](https://github.com/pynch-tv/Nexa/wiki).
