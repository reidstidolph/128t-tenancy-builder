# 128t-tenancy-builder
A model driven visualization of a 128T tenancy design

## Installation
To install the 128t-tenancy-builder, start by downloading or cloning this repo:
```
$ git clone https://github.com/reidstidolph/128t-tenancy-builder.git
```
Then serve up `index.html`, and all the other files with your favorite HTTP server.
(node.js based [http-server](https://www.npmjs.com/package/http-server) works well)
```
$ cd 128t-tenancy-builder
$ http-server
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://192.168.1.30:8080
Hit CTRL-C to stop the server
```
Finally, point your browser to your webserver and `index.html`.

## Customization
The entire diagram is completely rendered from `model.json`. To make your own diagram, use the included model as an example, and change it however you see fit.
