# Action Template

This is a template for building and releasing GitHub Actions.

## Using

When using this template, make sure and use _all_ branches. It is built with
the intent of release from the "release" branch, which removes the
distribution directory from its .gitignore file.

To build and release the action, merge changes from "main" into release, then
run `npm run build`. Commit these changes and create a new release from them.
