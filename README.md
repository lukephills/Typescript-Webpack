#Typescript and Webpack

####No Grunt, no Bower, no RequireJS needed.

Compile and bundle typescript applications and node modules with ease.

Following the great [article](http://www.jbrantly.com/typescript-and-webpack/) by [@jbrantly](https://github.com/jbrantly).

Install the node modules:
`npm install`

Install typscript definitions manager if you don't already have it.
`npm install -g tsd`

Install the typescript definition files:
`tsd install`

Install Webpack:
`npm install -g webpack`

Run webpack watch:
`webpack --watch`

Every time a typescript file is saved, Webpack will bundle all dependencies into a minified `bundle.js` file and create sourcemaps for debugging. In dev tools look at `webpack://` in the Sources panel.

I recommend using this method with [Atom](https://atom.io/) and [atom-typescript](https://atom.io/packages/atom-typescript) as it's super fast.
