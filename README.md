heroku-buildpack-pdfinput
========================

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Heroku Buildpack that that permits use of [pdf-fill-form >= 3](https://github.com/tpisto/pdf-fill-form). It does the following:

* Downloads libraries and header files from https://github.com/reqshark/pdfinput
* Sets appropriate CXXFLAGS and LDFLAGS for NodeJS buildpack to use.

Special thanks to @bdbau for suggesting the [pdfinput repo](https://github.com/reqshark/pdfinput) and the `pdfinput` repo itself.

## Usage
Add this buildpack before `node.js`. You could just add it to the top using:

```
heroku buildpacks:add --index 1 https://github.com/aatishnn/heroku-buildpack-pdfinput
```



