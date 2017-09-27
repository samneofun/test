
# VueJS 2 Install

Clone UI-Elements in desired drive

#### Install Node and NPM

## Install Vue-CLI
  
Install Vue-cli with webpack:

```shell
$ npm install -g vue-cli
```

###Install below required tools

```
? Project name: 
? Project description: 
? Author: 
? Vue build: Runtime-only
? Install vue-router? Y
? Use ESLint to lint your code? Y
? Pick an ESLint preset: none # we'll use a vue specific preset based on Standard
? Setup unit tests with Karma + Mocha? Y
? Setup e2e tests with Nightwatch? Y

vue-cli Generated "ui-elements"
```

###Install dependencies in `package.json`:

```shell
$ cd ui-elements 
$ npm install  # do this first before you add more dependencies (to avoid peer warns)
```

### Run the Dev Server

Run the dev server:

```shell
$ cd ~/ui-elements 
$ npm run dev
```

### Build application

```shell
$ cd ~/ui-elements 
$ npm run build
```
