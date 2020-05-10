# Nodejs Wrapper Tests

# Installing node-librealsense2

There are two ways to get node-librealsense2 module before testing: **install from npm** and **build from source**, both used **mocha** (`npm install mocha`) as test framework.

## Install From Npm

Used for feature validation in released node-librealsense2 module which updates bi-weekly.
Execute `npm i` under `/path/to/wrappers/nodejs/test` to download and install latest module from [npm](https://www.npmjs.com/package/node-librealsense2).

## Build From Source

Used for checking latest features in development branch which hasn't been released on npm.
Execute `npm list node-librealsense2` to check if you had installed node-librealsense2 before, if yes, remove it by using `npm remove node-librealsense2`

# Running the Tests

Use mocha to run test cases, for example:
Execute `mocha *.js` for all test cases under `/path/to/wrappers/nodejs/test`
or
Execute `mocha test-colorizer.js` for single test case
