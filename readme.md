A playground for testing npm, node, and related friends.

## Changelog
- v0.0.8 - hello world!  A very simple npm package, used in a very simple project.

## Try This
- **Create an npm package, and use it in a project.**  Try both methods: 1) import & use the package as a CommonJS / Node Module 2) import & use the package as an ES Module.  How do we ensure that Node imports the modules as ES Modules without complaining?  **Answer:** see v0.0.8.  **Further reading:** see the [Node docs](https://nodejs.org/docs/latest-v13.x/api/esm.html#esm_enabling) pay special attention to the significance of the `.mjs` file extension and the `"type": "module"` entry in the project's `package.json`.