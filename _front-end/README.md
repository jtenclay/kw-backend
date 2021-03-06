# Fabricator

> _fabricate_ - to make by assembling parts or sections.

Fabricator is a tool for building website UI toolkits - _think ["Tiny Bootstraps, for Every Client"](http://daverupert.com/2013/04/responsive-deliverables/#tiny-bootstraps-for-every-client)_

CSS, JS, Images, and Fonts are developed in `src/assets/toolkit/`

HTML partials in `src/materials` and full example pages in `src/views`


## Quick Start

Ensure you have *node.js* and *npm* installed. Node >=5.4.0 and NPM >=3.3.12 are known to work fine.

```shell
$ npm start
```

This will install dependencies into /node_modules. 

Once completed successfully. Run gulp as a build tool which will run a local server & watch for any changes to files in /src (compiling changes into /dist)

```shell
$ gulp 
```

However, *to compile assets for use in the webapp* ensure you run 
```shell
gulp --prod
``` 
after finished with development!!


## Documentation

#### [Read the docs →](http://fbrctr.github.io/docs)

## Demo

#### [Default Fabricator Instance →](http://fbrctr.github.io/demo)

## Credits

Created by [Luke Askew](http://twitter.com/lukeaskew)

Modified by [Duncan Bay](http://twitter.com/djtbay)

Logo by [Abby Putinski](https://abbyputinski.com/)

## License

[The MIT License (MIT)](http://opensource.org/licenses/mit-license.php)
