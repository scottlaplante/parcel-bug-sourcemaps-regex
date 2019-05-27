# parcel-bug-sourcemaps-regex

This repo demonstrates a bug with parcel's regex treatment of source maps.

To replicate behavior:

### Correct behavior
1. run `node index.js`

### Incorrect behavior
1. first, install dependencies
2. then run `parcel index.js -d dist`
3. finally run `node dist/index.js`

Note that the output differs
