## create-react-app-issue-4167

This branch recreates the example provided by @timer [here](https://github.com/facebook/create-react-app/issues/4167#issuecomment-449763638).

This branch, when using `yarn` version `1.13.0` properly hoists `webpack@3` to the root `node_modules` directory, and installs `webpack@4` locally in the `node_modules` directory for the one  package that depends on it.
