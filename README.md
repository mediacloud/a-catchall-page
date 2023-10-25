# Catchall page app

If you have a wildcard DNS record pointing to a Dokku server, and you
enter a domain name for which there is no app running on the server,
you seem to end up on the lexicographically first app, which in our
case is an API server that gives unhelpful information.

This repository (index.html and .static files) is for creating an
a-static-page dokku app, that serves the index.html as a static document.

