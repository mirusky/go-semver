# Go Semver

It's a hello world repository using [go-semantic-release/action](https://github.com/go-semantic-release/action) to automatically set the Semantic Version.

## How does it work ?

It create a new version based on commit messages following the [AngularJS Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit). Every time a commit is made on `master` branch it will check the commit and then release a new version.

## I want to use it

Check the [ci.yml](../.github/workflows/ci.yml) file for more information.