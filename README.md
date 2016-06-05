# daddaddaddyo
A really simple example of building a static site with harpjs.

#### Setup
Harp must be installed globally to serve/build project
```
npm install -g harp
```

#### Serving
For local development, serve the _src directory.
```
harp server _src
```

#### Building
To generate static files for deployment, compile the _src directory into www.
```
harp compile _src www
```
