# learning-npm
First npm package

## Testing
 - go to '/consuming-package'
 - run 'npm install'
 - run 'npm test'

## What happens

 Dir 'consuming-package' contains a js file that depends on a npm package, this dependency is listed in package.json,
 when 'npm install' is ran, this dependency is donwloaded from npm registry.

 The repo of the package itself is also this one, the contents of the package are under '/package'.

 When 'npm test' is ran, the script specified under 'scripts/test/' in package.json is run and you should see:
 'first npm package' print to console.
