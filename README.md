# Test Project - Implement a Modal form save and addition of entry to a Table

**Terms**

- The expected time to complete is under 2 hours
- You will be given access to an existing repo of an admin template will all the necessary UI elements already provided
- You are expected to implement the feature using the already provided UI elements/kit from the admin template repo

**GitHub** **Repo**: [https://github.com/iamport-intl/admin-template](https://github.com/iamport-intl/admin-template)

**Problem statement**

- Build frontend in Vue.js for the requirement
- Use the Vuejs Admin template that we provide
- **Implement the feature and raise pull request (PR) against the above repo**
- **We will review the PR and get back to you**

**Basic CRUD page** - **High-Level Requirements**

- A CRUD page to create payment links - Refer to the screenshot
    - CRUD page will have a table - the table will show a list of created payment links
    - A 'Create' Action on the top right
    - Create Action will open a modal for payment link creation
    - Templates to use
        - Table templates demo - [https://coreui.io/vue/demo/free/3.1.1/#/base/tables](https://coreui.io/vue/demo/free/3.1.1/#/base/tables)


- Modal for payment link creation - Refer to the screenshot
    - Amount field - validation with only positive decimal numbers - required field
    - Currency drop-down - required fields
    - Customer name, email, and phone fields with email and phone validations - optional fields
    - **Ignore other fields in the Screenshot - need not implement those**
    - After creation, the payment link should be added to the table
        - Only update the vuex store
        - Need not use any backend
    - Payment links are only created. No need to provide an update or delete operations
    - Templates to use
        - Form samples - [https://coreui.io/vue/demo/free/3.1.1/#/base/forms](https://coreui.io/vue/demo/free/3.1.1/#/base/forms)
        - Modal dialogs - [https://coreui.io/vue/demo/free/3.1.1/#/notifications/modals](https://coreui.io/vue/demo/free/3.1.1/#/notifications/modals)




# CoreUI Free Vue Bootstrap Admin Template

[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=CoreUI%20-%20Free%20Vue%20Admin%20Template%20&url=http://coreui.io/vue/&hashtags=bootstrap,admin,template,dashboard,panel,free,angular,react,vue)
[![NPM][npm-coreui-vue-badge-latest]][npm-coreui-vue]
[![Downloads](https://img.shields.io/npm/dm/@coreui/vue.svg?style=flat-square)][coreui]
[![Vue](https://img.shields.io/badge/Vue-^2.6.11-brightgreen.svg?style=flat-square)][coreui]

[![Project check](https://github.com/coreui/coreui-free-vue-admin-template/actions/workflows/project-check.yml/badge.svg)](https://github.com/coreui/coreui-free-vue-admin-template/actions/workflows/project-check.yml)
[![Daily project check](https://github.com/coreui/coreui-free-vue-admin-template/actions/workflows/daily-project-check.yml/badge.svg)](https://github.com/coreui/coreui-free-vue-admin-template/actions/workflows/daily-project-check.yml)

[npm-coreui-vue]: https://www.npmjs.com/package/@coreui/vue
[npm-coreui-vue-badge-latest]: https://img.shields.io/npm/v/@coreui/vue/latest?style=flat-square&color=brightgreen  
[coreui]: https://coreui.io/vue

![Template](https://coreui.io/images/github/vue-free-template-3.gif)

## Description

Why we decided to create CoreUI? Please read this article: [Jack of all trades, master of none. Why Boostrap Admin Templates suck.](https://medium.com/@lukaszholeczek/jack-of-all-trades-master-of-none-5ea53ef8a1f#.7eqx1bcd8)

**This is not just another Admin Template.** It goes way beyond hitherto admin templates thanks to:

- Wonderful styling delivered by bootstrap compatible css library [CoreUI](https://coreui.io/docs/3.0-beta/),
- Dedicated [component library](https://coreui.io/vue/docs/),
- Dedicated vue tooling libraries ([coreui-vue-chartjs](https://coreui.io/vue/docs/components/charts), [coreui-icons-vue](https://github.com/coreui/coreui-icons-vue)),
- Over 500 [free svg icons](https://coreui.io/icons) consistent with our styling,
- Transparent code and file structure
- Possibility of extension to [pro version](https://coreui.io/vue) which offers even more!

CoreUI is meant to be the UX game changer. Pure & transparent code is devoid of redundant components, so the app is light enough to offer ultimate user experience. This means mobile devices also, where the navigation is just as easy and intuitive as on a desktop or laptop. The CoreUI Layout API lets you customize your project for almost any device – be it Mobile, Web or WebApp – CoreUI covers them all!

**NOTE:** Please remember to star this project to get new versions updates of this template.

### Demo

A fully functional demo is available at [CoreUI](http://coreui.io/vue/)

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [License](#copyright-and-license)

### Installation

#### Clone repo

``` bash
# clone the repo
$ git clone https://github.com/coreui/coreui-free-vue-admin-template.git CoreUI-Vue

# go into app's directory
$ cd CoreUI-Vue

# install app's dependencies
$ npm install
```

#### Usage

``` bash
# serve with hot reload at localhost:8080
npm run serve

# build for production with minification
npm run build

# run linter
npm run lint

# run unit tests
npm run test:unit

# run e2e tests
npm run test:e2e

```

For a detailed explanation on how things work, check out the [Vue CLI Guide](https://cli.vuejs.org/guide/).

### Documentation

CoreUI tools documentation:

- Components documentation: [CoreUI Vue library](https://coreui.io/vue/docs)
- Styles documentation: [CoreUI styles](https://coreui.io/docs/3.0-beta/)
- Icons documentation: [CoreUI Icons](http://coreui.io/icons)

### Bugs and feature requests

Have a bug or a feature request? [Please open a new issue](https://github.com/coreui/coreui-free-vue-admin-template/issues).

### Contributing

Please read through our [contributing guidelines](https://github.com/coreui/coreui-free-vue-admin-template/blob/master/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

### Versioning

For transparency into our release cycle and in striving to maintain backward compatibility,CoreUI Free Admin Template is maintained under [the Semantic Versioning guidelines](http://semver.org/).

See [the Releases section of our project](https://github.com/coreui/coreui-free-vue-admin-template/releases) for changelogs for each release version.


## Copyright and license

Copyright 2020 creativeLabs Łukasz Holeczek. Code released under [the MIT license](https://github.com/coreui/coreui-free-vue-admin-template/blob/master/LICENSE).
There is only one limitation - you cannot re-distribute the `CoreUI` as stock nor if you modify the `CoreUI`. In the past we faced some problems with persons who tried to sell `CoreUI` based templates.

## Support CoreUI Development

CoreUI is an MIT licensed open source project and completely free to use. However, the amount of effort needed to maintain and develop new features for the project is not sustainable without proper financial backing. You can support development by buying [PRO version](https://coreui.io/pro/).
