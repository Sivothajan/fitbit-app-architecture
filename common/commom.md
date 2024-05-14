# Shared Code
## /common/

Files within this folder can be shared between the application and companion to minimize duplication. Create each file as an [ES6 module](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/import), then import that module into your application or companion.

The build process will automatically perform [tree shaking](https://rollupjs.org/#tree-shaking) to exclude any unused modules from the final output.
