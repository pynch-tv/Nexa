# Nexa
A RESTful API to EVS Audio Video Servers.

HTTP and the web have become the lingua-franca in the ICT world and have found their entry in the broadcast world as well. But not all machines in the broadcast world (old and new) want to expose such an HTTP interface to the outside world: not part of the offering, not to make it easy to interface with and stay within the product family (vendor lock-in).

With Nexa we want to provide an HTTP RESTful API on top of existing audio video production servers - made for the broadcast integrators and programmers.

## Design Philosophy

We want to API to be instant recognizable by programmers and broadcast engineers! How? By applying all the industry best-practices and API guidelines put forward by industry: [W3C](w3c.org), [IETF](ietf.org), [OGC](ogc.org), [industry best practices](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/) and [government API Design Rules](https://gitdocumentatie.logius.nl/publicatie/api/adr/).

By following the well-known API patterns, developers can get their first successful call within minutes [TTFC](https://nordicapis.com/why-time-to-first-call-is-a-vital-api-metric) (The time taken between a developer accessing documentation, and/or signing up for an API key and making their first successful API call (of any complexity)). Additionally, by following the best practices, AI coding assistants (eg [GitHub's Co-Pilot](https://github.com/features/copilot)) can predict code more easely and accuratly.
