# SR Creation API documentation

## Setup

To setup, navigate to `src`, then run a simple server to serve the `.yaml` OpenAPI documents:

    python -m SimpleHTTPServer

By default, this will expose the files on localhost via port 8000.  If configured otherwise, make sure to change the port in `index.html`.

## Run

You can view the docs by following **Setup**, then opening `index.html` in a browser.  You will also need to have CORS enabled to serve the OpenAPI docs locally.  We suggest using [this Chrome extension](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en).

## Information

The API docs attempt to follow [OpenAPIv3](https://github.com/OAI/OpenAPI-Specification/blob/master/README.md) specifications, except for at times when [ReDoc](https://github.com/Rebilly/ReDoc/) does not accept these standards or when [ReDoc](https://github.com/Rebilly/ReDoc/) expects additional parameters.

[ReDoc](https://github.com/Rebilly/ReDoc/) is used to render the OpenAPI files as static HTML.