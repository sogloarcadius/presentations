# Presentations using Reveal.js

## Read online

[https://sogloarcadius.github.io/presentations](https://sogloarcadius.github.io/presentations)

## Read locally

### Install tools and dependencies

```sh
#install grunt and make it available globally
npm install -g grunt

# install bower
npm install -g bower

# install dependencies in package.json using orange registry
npm install

# install reveal.js using bower (check .bowerrc for registry configuration)
bower install
```

### Open the presentation

```sh
grunt serve
```

### Export as PDF

The server must be up and running then in a **chrome web browser** go to [http://localhost:9000/?print-pdf](http://localhost:9000/?print-pdf) and print (Ctrl + P) the web page.








