# webpack-demo

Basic Setup
First let's create a directory, initialize npm, install webpack locally, and install the webpack-cli (the tool used to run webpack on the command line):

mkdir webpack-demo
cd webpack-demo
npm init -y
npm install webpack webpack-cli --save-dev

To bundle the lodash dependency with index.js, we'll need to install the library locally:

npm install --save lodash

R
Run the build again but instead using our new configuration file:

$ npx webpack --config webpack.config.js

npm run build
