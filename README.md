![TyLauncher-logo](https://raw.githubusercontent.com/luckytianyiyan/tylauncher.com/gh-pages/README_RES/tylauncher-logo.png)
[![GitHub License](https://img.shields.io/github/license/luckytianyiyan/tylauncher.com.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

The [website](http://www.tylauncher.com) for [TyLauncher](https://github.com/luckytianyiyan/TyLauncher).
### Build

This is a [Jekyll](http://jekyllrb.com) site hosted on [GitHub Pages](http://pages.github.com).
To build a Jekyll site you'll need a few things on your system so double check the [Jekyll requirements](http://jekyllrb.com/docs/installation/#requirements).
In addition to those, you'll need these Ruby gems:

```bash
$ gem install jekyll
$ gem install bundler
```
Follow these steps to copy this repository to your computer and build the site:

```bash
$ git clone https://github.com/luckytianyiyan/TyLauncher.git
$ cd tylauncher.com
$ script/bootstrap
$ script/server
```

### CLI for Releases

You'll need Node.js installed on your system in order to use the CLI. Then you can install the dependencies:
```
$ cd tylauncher.com
$ npm install
```

#### Release Notes

The most recent release notes from the luckytianyiyan/TyLauncher repository are made available on the site and can be updated by running:
```
$ script/releases
```

### OSS used in `tylauncher.com`

One of the reasons `tylauncher.com` is real is the following OSS projects:

  1. [electron.atom.io](https://github.com/atom/electron.atom.io)
  2. [jekyll-multiple-languages-plugin](https://github.com/screeninteraction/jekyll-multiple-languages-plugin)

    > Note: jekyll-multiple-languages-plugin v1.3.0, Jekyll 3 incompatibility.

    see [jekyll-multiple-languages-plugin issues#52](https://github.com/screeninteraction/jekyll-multiple-languages-plugin/issues/52)

    tylauncher.com use [@Anthony Gaudino](https://github.com/Anthony-Gaudino)'s repository (branch: v1_4_0):

    [Anthony-Gaudino/jekyll-multiple-languages-plugin](https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin/tree/v1_4_0)

### License

`tylauncher.com` is available under the `MIT` license. See the LICENSE file for more info.
