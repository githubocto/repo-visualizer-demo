# repo-visualizer Demo

This is an example of using the [repo-visualizer](https://github.com/githubocto/repo-visualizer) GitHub Action.

We've included the generated diagram by adding it to the README:

![Visualization of this repo](./diagram.svg)

You can check out the whole GitHub Action at [diagram.yml](/.github/workflows/diagram.yml). Notice that we're excluding the `ignore` and `.github` folders, using the `excluded_paths` config.
