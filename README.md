# Docsy

[![Project status: active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Project releases](https://img.shields.io/github/release/pasabanov/docsy)](https://github.com/pasabanov/docsy/releases)
[![Project contributors](https://img.shields.io/github/contributors/pasabanov/docsy)](https://github.com/pasabanov/docsy/graphs/contributors)
[![Project license](https://img.shields.io/github/license/pasabanov/docsy)](https://github.com/pasabanov/docsy/blob/main/LICENSE)

> **🚧 WARNING 🚧 : `main` is under development and potentially unstable! Use
> official Docsy [releases].**

Docsy is a [Hugo](https://gohugo.io) theme for technical documentation sets,
providing simple navigation, site structure, and more.

This is not an officially supported Google product. This project is actively
being maintained.

This project is a fork of [google/docsy](https://github.com/google/docsy).
As part of the modifications, references to google have been replaced with my personal GitHub username. While care was taken during this process, some links or references may have been inadvertently updated incorrectly. If you notice any issues, feel free to open a pull request or an issue.

## Prerequisites

The following are basic prerequisites for using Docsy in your site:

- Install a recent release of the Hugo "extended" version. If you install from
  the [Hugo release page](https://github.com/gohugoio/hugo/releases), make sure
  you download the `extended` version, which supports SCSS.

- Install `PostCSS` so that the site build can create the final CSS assets. You
  can install it locally by running the following commands from the root
  directory of your project:

  ```sh
  npm install --save-dev autoprefixer
  npm install --save-dev postcss-cli
  ```

  Starting in
  [version 8 of `postcss-cli`](https://github.com/postcss/postcss-cli/blob/master/CHANGELOG.md),
  you must also separately install `postcss`:

  ```sh
  npm install -D postcss
  ```

Any additional prerequisites depend on the
[installation option](https://www.docsy.dev/docs/get-started/#installation-options)
you choose. We recommend using Docsy as a Hugo module, which requires that you
have the Go language installed in addition to Hugo and PostCSS.

For complete prerequisites and instructions, see our
[Get started guides](https://www.docsy.dev/docs/get-started/).

## Example and usage

You can find an example project that uses Docsy in the
[Docsy Example Project repo](https://github.com/pasabanov/docsy-example).The Docsy
Example Project is hosted at [example.docsy.dev](https://example.docsy.dev). For
real-life examples of sites that use Docsy (and their source repos), see our
[Examples](https://www.docsy.dev/docs/examples/) page.

To use the Docsy theme for your own site:

- (Recommended) Use the
  [example project](https://github.com/pasabanov/docsy-example), which includes the
  Docsy theme as a Hugo module, as a template to create your project. You can
  customize this pre-configured basic site into your own Docsy themed site.
  [Learn more...](https://github.com/pasabanov/docsy-example)

- Add Docsy to your existing Hugo site. You can add Docsy as a Hugo module, as a
  Git submodule, or clone the Docsy theme into your project.

See the [Get started guides](https://www.docsy.dev/docs/get-started/) for
details about the various usage options.

## Documentation

You can use Hugo to generate and serve a local copy of the guide
(also useful for testing local theme changes), making sure you have installed
all the prerequisites listed above:

```sh
git clone --depth 1 https://github.com/pasabanov/docsy.git
cd docsy/userguide/
npm install
npm run serve
```

## Contributing

For details on our [code of conduct] and the process for submitting pull
requests, see [CONTRIBUTING.md]. Thank you to all past, present, and future
[contributors]!

## License

This project is licensed under the Apache License 2.0 - see
[LICENSE](https://github.com/pasabanov/docsy/blob/main/LICENSE) for details

[code of conduct]:
  https://github.com/google/.github/blob/master/CODE_OF_CONDUCT.md
[CONTRIBUTING.md]: https://github.com/pasabanov/docsy/blob/main/CONTRIBUTING.md
[contributors]: https://github.com/pasabanov/docsy/graphs/contributors
[releases]: https://github.com/pasabanov/docsy/releases
