# SUMMARY #

## EJS ##
- EJS let's us spin up quick applications when we don't need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.
- EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.
- It's easy to debug EJS errors: your errors are plain JavaScript exceptions, with template line-numbers included.

### Features ###
1. Fast compilation and rendering.
1. Simple template tags: <% %>
1. Custom delimiters (e.g., use <? ?> instead of <% %>)
1. Includes.
1. Both server JS and browser support.
1. Static caching of intermediate JavaScript.
1. Static caching of templates.
1. Complies with the Express view system.

![image](https://miro.medium.com/max/850/1*usicWavHRKy4Sjm2XTCBMA.jpeg)


## Using the API ##
**Authorizing requests and identifying your application**
- Every request your application sends to the Books API needs to identify your application to Google. There are two ways to identify your application: using an OAuth 2.0 token (which also authorizes the request) and/or using the application's API key. Here's how to determine which of those options to use:
1. If the request requires authorization (such as a request for an individual's private data), then the application must provide an OAuth 2.0 token with the request. The application may also provide the API key, but it doesn't have to.
1. If the request doesn't require authorization (such as a request for public data), then the application must provide either the API key or an OAuth 2.0 token, or both—whatever option is most convenient for you.

