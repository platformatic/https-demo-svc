# Demonstrate HTTPS support

1. Start service with `npm start`
2. Make failing HTTPS request: `curl -D - https://localhost:3042`
3. Make successful HTTP request: `curl -D - http://localhost:3042`

Note that `npm start` logs the `http://` URL
