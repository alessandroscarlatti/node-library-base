# Node Library Base

This project can be a starting point to understand the basic code necessary to build a library with NodeJS.

# How to Build
The project currently builds the library module using Webpack.
To build the library, run `npm run build`.  The bundled library will be generated into `/dist/mumbo.js`.

# How to Use
The library is bundled in "UMD" format, so it is usable with a variety of module loaders.
With "RequireJS", for example the library could be used this way:

```
const mumbo = require("./mumbo")
```