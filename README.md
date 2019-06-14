# Html-Minifier for ES6 (incl. TS definitions)
This is a fork that adds a quick & dumb uglifying support for ES6

# Actual repo
<https://github.com/kangax/html-minifier>


# How to use

Add manually `"html-minifier": "git+https://github.com/crafter999/html-minifier.git"` to package.json dependencies.

````
...
"dependencies": {
  ...
  "html-minifier": "git+https://github.com/crafter999/html-minifier.git",
  ...
}
...
````

Enable it using "es6" in `minifyJS` options like the following example
````
minify(html, {
  removeComments: true,
  minifyJS: "es6", // <------
  collapseWhitespace: true
});
````
