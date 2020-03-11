# Westley's React Material-UI Template

This can be used to quickly start new projects with React and Material-UI.

It also includes Jest and a Webpack bundler.

The Webpack scripts will need additional configuration to handle css files.

# Getting Started

-   Clone this repository
-   Run `npm i && npm i -D` to install all of the dependencies
-   Create a `.env` file to store secrets. All secrets must be prepended with 'REACT_APP\_' or they will be ignored by the Webpack bundler.
-   Update the meta attributes in `index.html` and line 76 in `build-utils/webpack.common.js`
-   Run `npm run dev` to start a development server on the local host and view the application
-   Run `npm run build` to generate a production-ready bundle. This is useful for analyzing final bundle size.

### Scripts

| npm run    | Description                                                                                                                                                                                                                                         |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dev        | Starts a webpack-dev-server for development. Opens in default browser. Automatically updates on save.                                                                                                                                               |
| build      | Create a minified production build. Files are output to /public. The complete contents of /public are overwritten each time this script is executed. /public is ignored by git. To inspect the output of the build command open the /public folder. |  |
| format     | Recursively format all .js and .jsx files in the /src directory.                                                                                                                                                                                    |
| lint       | Run Eslint and report errors found by recursively searching and analyzing all javascript files in the /src directory.                                                                                                                               |
| test       | Run the Jest test suite once.                                                                                                                                                                                                                       |
| test:watch | Run the Jest test suite in `watch` mode. The test suite will run when a file used in tests is updated.                                                                                                                                              |
