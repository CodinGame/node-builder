# node-npm-builder

# What it Does

This nodeJS builder copies the contents of the project's root to the `/project/target` directory, then installs the dependencies using `npm install`. The dependencies must be specified in the `package.json` file at the project root as specified in the [official documentation](https://docs.npmjs.com/getting-started/using-a-package.json).

# How to Use

In order to use this builder for your project, edit the `codingame.yml` file and add the following lines to your project:

    builder:
      name: codingame/node-npm-builder
      version: 1.0

# Compatibility

This builder can be used by a node runner using the project in `/project/target`.

Compatible with `node-mocha-runner`.