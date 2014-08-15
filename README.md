Go-Rest
=======
This contains the Workiva standard REST API client and server implementations for Go.

# Server

This contains the APIs for implementing a RESTful web service. The goal is to provide
a framework that makes it easy to build a flexible and (mostly) unopinionated REST API with
little ceremony. It's platform-agnostic, meaning it works both on- and off- App Engine, and
pluggable in that it supports custom response serializers, middleware and authentication.

See the examples to get started.

# Client

The rest package also contains a client implementation for consuming REST APIs.  It
includes pluggable request authorization and response deserialization.

NOTICE
------
Requirements to commit here:
  
  - Branch off master, PR back to master.
  - [gofmt](http://golang.org/cmd/go/#hdr-Run_gofmt_on_package_sources) your code. Unformatted code will be rejected.
  - Follow the style suggestions found [here](https://code.google.com/p/go-wiki/wiki/CodeReviewComments).
  - Unit test coverage is required.
  - Good docstrs are required for at least exported names, and preferably for all functions.
  - Good [commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) are required.
