# Reify/ESM Bug

This repo is a minimal reproducible example of an existing bug with [Reify](https://github.com/benjamn/reify) when importing a module that
uses [esm](https://github.com/standard-things/esm).

If you import the esm package into server-side code. You will receive a "module.export is not a function" error.

I believe this started in Meteor 2.3.0, when Node was updated to V14
