# Onboarding Experiments 🙈

Here we keep a live version of some experiments we are trying for the onboarding process.

For the production repository check here:

https://github.com/fablabbcn/smartcitizen-onboarding-app

### Prerequisites

You need git to clone the repository. You can get git from
[http://git-scm.com/](http://git-scm.com/).

We also use a number of node.js tools to initialize and test the Web App. You must have node.js and
its package manager (npm) installed. You can get them from [http://nodejs.org/](http://nodejs.org/).

Also gulp: `npm install -g gulp` (with `sudo` if you are using Mac).
### Clone the project

Clone the repository using:

```
git clone https://github.com/fablabbcn/smartcitizen-onboarding.git
cd smartcitizen-web
```

### Install dependencies
* Install tools to manage and test the application: `npm install.`
* No need of `bower install`, `npm install` will take care of it.

### Use Gulp tasks

* `gulp` or `gulp build` to build an optimized version of your application in `/dist`
* `gulp serve` to launch a browser sync server on your source files
* `gulp serve:dist` to launch a server on your optimized application
* `gulp test` to launch your unit tests with Karma
* `gulp test:auto` to launch your unit tests with Karma in watch mode
* `gulp protractor` to launch your e2e tests with Protractor
* `gulp protractor:dist` to launch your e2e tests with Protractor on the dist files
* `gulp deploy` to publish the project to Github pages (gh-pages branch).

Note: in case you see something like:
> Error: Command failed: fatal: unable to read c6a8d370f3e95d9110eca4a03b704bd8940ca40b

Run:
`rm -Rf $(node -e "console.log(require('path').join(require('os').tmpdir(), 'tmpRepo'))")`


*This is a Work in process... Final documentation coming soon!*

### Support and issues

* Forum [forum.smartcitizen.me](http://forum.smartcitizen.me)

### Credits

This work has received funding from the European Union's Horizon 2020 research and innovation program under the grant agreement No. 688620

[![DOI](https://zenodo.org/badge/74163605.svg)](https://zenodo.org/badge/latestdoi/74163605)
