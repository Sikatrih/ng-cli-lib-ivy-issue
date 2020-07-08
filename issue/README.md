Steps for reproduce:

ng build my-lib --prod
cd dist/my-lib/
npm publish

gets error
ERROR: Trying to publish a package that has been compiled by Ivy. This is not allowed.
Please delete and rebuild the package, without compiling with Ivy, before attempting to publish.
