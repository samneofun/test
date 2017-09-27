
# VueJS 2 Install

Install Vue-cli, VueRouter, VueResource. Clone the repo, do `npm install`, and use right away or read through this tutorial below to get an idea of how to build the project from scratch and setup Sublime Text.

## Table of Contents
1. [UI Elements](#UI Elements)
2. [Install Node](#install-node)
3. [Install Vue-CLI](#install-vue-cli)
4. [Add Dependencies](#add-dependencies)
5. [Configure ESLint](#configure-eslint)
6. [Setup Main and Routes](#setup-main-and-routes)
7. [Setup Authentication (OAuth2), User Profile, and Vuex](#setup-authentication-user-profile-and-vuex)
8. [Proxy Api Calls in Webpack Dev Server](#proxy-api-calls-in-webpack-dev-server)
9. [Unit Testing and End-to-End Testing](#unit-testing-and-end-to-end-testing)
10. [Run the Dev Server](#run-the-dev-server)



#### Install Node and NPM

## Install Vue-CLI
  
Install Vue-cli with webpack:

```shell
$ npm install -g vue-cli
```

Now you'll get some output like this:

```
? Project name: ui-elements
? Project description: A Vue.js project
? Author: Your Name <your-name@email.com>
? Vue build: Runtime-only
? Install vue-router? Y
? Use ESLint to lint your code? Y
? Pick an ESLint preset: none # we'll use a vue specific preset based on Standard
? Setup unit tests with Karma + Mocha? Y
? Setup e2e tests with Nightwatch? Y

vue-cli Generated "ui-elements"
```

Install dependencies in `package.json`:

```shell
$ cd ui-elements 
$ npm install  # do this first before you add more dependencies (to avoid peer warns)
```

## Run the Dev Server

Run the dev server:

```shell
$ cd ~/ui-elements 
$ npm run dev
```
