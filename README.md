# [Bootstrap](https://getbootstrap.com/)

Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thornton](https://twitter.com/fat), and maintained by the [core team](https://github.com/orgs/twbs/people) with the massive support and involvement of the community.

To get started, check out <https://getbootstrap.com/>!

This repository is a fork of original Bootstrap but only version 3. This is to make it use new functions and syntax and work with modern web browsers.  
There is no new or extra features than original Bootstrap 3 and no new feature request here.


## Table of contents

* [Limitations](#limitations)
* [Quick start](#quick-start)
* [Bugs and feature requests](#bugs-and-feature-requests)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [Community](#community)
* [Versioning](#versioning)
* [Creators](#creators)
* [Thanks](#thanks)
* [Copyright and license](#copyright-and-license)


## Limitations

This repo. use CSS variable for example `--background-color: #fff;` and `background-color: var(--background-color);`. So, it does not supported Internet Explorer (IE). If you would like to use old browsers, please use original Bootstrap 3.

This repo. use [CSS relative color syntax](https://caniuse.com/css-relative-colors) and it currently does not supported in all web browsers yet. Please check for current support on a link.


## Quick start

Several quick start options are available:

* [Download the latest release](https://github.com/rundiz/bootstrap3/archive/v3.4.1.zip).
* Clone the repo: `git clone https://github.com/rundiz/bootstrap3.git`.

Read the [Getting started page](https://getbootstrap.com/docs/3.4/getting-started/) for information on the framework contents, templates and examples, and more.

### What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   ├── bootstrap-theme.min.css
│   └── bootstrap-theme.min.css.map
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

We provide compiled CSS and JS (`bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`). CSS [source maps](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps) (`bootstrap.*.map`) are available for use with certain browsers' developer tools. Fonts from Glyphicons are included, as is the optional Bootstrap theme.


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/rundiz/bootstrap3/blob/v3-dev/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/rundiz/bootstrap3/issues/new).

Do not accept feature requests. This repository is for make Bootstrap 3 using modern functions, syntax to use with moder web browsers but keep original features of Bootstrap 3. No new feature requests.

## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](https://jekyllrb.com/) and publicly hosted on GitHub Pages at <https://getbootstrap.com/>. The docs may also be run locally.

### Running documentation locally

#### Use local command
1. If necessary, [install Jekyll](https://jekyllrb.com/docs/installation/) and other Ruby dependencies with `bundle install`.
   **Note for Windows users:** Read [this guide](https://jekyllrb.com/docs/installation/windows/) to get Jekyll up and running without problems.
2. From the root `/bootstrap` directory, run `bundle exec jekyll serve` in the command line.
4. Open `http://localhost:9001` in your browser, and voilà.

#### Use Docker
1. Install [Docker](https://www.docker.com/) and then install [Docker image named **jekyll**](https://hub.docker.com/r/jekyll/jekyll/) via command `docker pull jekyll/jekyll:3.8.6`.
2. Run Docker image via command `docker run --rm -it --volume="%cd%:/srv/jekyll" --publish 9001:9001  jekyll/jekyll:3.8.6 jekyll serve`. You may replace `%cd%` to `$PWD` on Linux.  
  You may use command `docker run --rm -it --volume="%cd%:/srv/jekyll" --publish 9001:9001  jekyll/jekyll:3.8.6 jekyll serve --force_polling --livereload` to make it auto regenerate the document on Windows.
3. Open `http://localhost:9001/docs/3.4/` in your browser.

Learn more about using Jekyll by reading its [documentation](https://jekyllrb.com/docs/).


## Contributing

Please read through our [contributing guidelines](https://github.com/rundiz/bootstrap3/blob/v3-dev/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/rundiz/bootstrap3/tree/v3-dev/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

**Bootstrap v3 is now closed off to new features.**

Editor preferences are available in the [editor config](https://github.com/rundiz/bootstrap3/blob/v3-dev/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.


## Community

Get updates on Bootstrap's development and chat with the project maintainers and community members.

* Follow [@getbootstrap on Twitter](https://twitter.com/getbootstrap).
* Read and subscribe to [The Official Bootstrap Blog](https://blog.getbootstrap.com/).
* Join [the official Slack room](https://bootstrap-slack.herokuapp.com/).
* Chat with fellow Bootstrappers in IRC. On the `irc.freenode.net` server, in the `##bootstrap` channel.
* Implementation help may be found at Stack Overflow (tagged [`twitter-bootstrap-3`](https://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).
* Developers should use the keyword `bootstrap` on packages which modify or add to the functionality of Bootstrap when distributing through [npm](https://www.npmjs.com/search?q=keywords:bootstrap) or similar delivery mechanisms for maximum discoverability.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we'll adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/rundiz/bootstrap3/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](https://blog.getbootstrap.com/) contain summaries of the most noteworthy changes made in each release.


## Thanks

<img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack Logo" width="490" height="106">

Thanks to [BrowserStack](https://www.browserstack.com/) for providing the infrastructure that allows us to test in real browsers!


## Creators

**Mark Otto**

* <https://twitter.com/mdo>
* <https://github.com/mdo>

**Jacob Thornton**

* <https://twitter.com/fat>
* <https://github.com/fat>


## Copyright and license

Code and documentation copyright 2011-2019 Twitter, Inc. Code released under [the MIT license](https://github.com/rundiz/bootstrap3/blob/v3-dev/LICENSE). Docs released under [Creative Commons](https://github.com/rundiz/bootstrap3/blob/v3-dev/docs/LICENSE).
