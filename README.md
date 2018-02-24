# browserify global demonstration

See it running [here](http://konsumer.js.org/so22823203/)

Here is a demo of 2 methods of exposing a global with browserify, as an illustration for [this stack overflow](https://stackoverflow.com/questions/22823203/how-to-access-a-variable-declared-within-browserify-script/25494746#25494746)

1. `global_build` - use build command (`npm run build:standalone`) to expose the exported interface as a global
2. `global_expose` - use `global.globalExpose` to expose it directly

## to demo

1. `npm run build:standalone`
2. `npm run build:expose`
3. `open pub/index.html`
