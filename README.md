# Westley's React Material-UI Template

This can be used to quickly start new projects with React and Material-UI.

It also includes Jest and a Webpack bundler.

The Webpack scripts will need additional configuration to handle css files.

Update the meta attributes in index.html and line 76 in build-utils/webpack.common.js

# Usage

-   Clone this repository
-   Run `npm i && npm i -D` to install all of the dependencies
-   Create a `.env` file to store secrets. All secrets must be prepended with 'REACT_APP\_' or they will be ignored by the Webpack bundler.
-   Run `npm run dev` to start a development server on the local host and view the application
-   Run `npm run build` to generate a production-ready bundle. This is useful for analyzing final bundle size.
