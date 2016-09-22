#####################################
HARP - CLI tool for parsing HAR files
#####################################

CLI tool to parse and analyze `HTTP Archive (HAR)`_ files.

.. _HTTP Archive (HAR): https://en.wikipedia.org/wiki/.har


(Planned) features
==================

- List / filter requests contained in the archive
- Replay a specific given request
  - And analyze differences between subsequent responses
- Print differences between requests in the file
- Replay modified requests and see how that affects the response


Main use cases
==============

There might be many, but in my specific case I need to analyze the
behavior of (overly complex!) search forms for crawling purposes, see
how requests are made, and which parts of the request will affect the
response.
