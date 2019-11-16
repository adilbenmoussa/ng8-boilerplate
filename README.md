# Angular 8 - Boilerplate

[![](https://github.com/smarlhens/ng8-boilerplate/workflows/CI/badge.svg)](https://github.com/smarlhens/ng8-boilerplate/actions?query=workflow%3ACI)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.14.

## Table of contents 
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [What's in the box ?](#whats-in-the-box-)
  - [Commitizen](#commitizen)
  - [Commitlint](#commitlint)
  - [ESLint](#eslint)
  - [GitHub Actions](#github-actions)
  - [Husky](#husky)
  - [Lint-staged](#lint-staged)
  - [Prettier](#prettier)
  - [Stylelint](#stylelint)
- [Code scaffolding](#code-scaffolding)
- [Build](#build)
- [Running unit tests](#running-unit-tests)
- [Running end-to-end tests](#running-end-to-end-tests)
- [Further help](#further-help)
---

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them : 

* [Git](https://git-scm.com/)
* [Angular CLI](https://cli.angular.io/) *installed globally recommended*

### Installation

1. Clone the git repository

   ```bash
   git clone https://github.com/smarlhens/ng8-boilerplate.git
   ```

1. Go into the project directory

   ```bash
   cd ng8-boilerplate/
   ```

1. Checkout working branch

   ```bash
   git checkout <branch>
   ```

---

## What's in the box ?

### Commitizen

[commitizen](https://github.com/commitizen/cz-cli) is a command line utility that makes it easier to create commit messages following the [conventional commit format](https://conventionalcommits.org) specification.

Use ```git cz``` instead of ```git commit``` to use commitizen.

[![Add and commit with Commitizen](https://github.com/commitizen/cz-cli/raw/master/meta/screenshots/add-commit.png)](https://github.com/commitizen/cz-cli/raw/master/meta/screenshots/add-commit.png)

**Configuration file**: ```.czrc```.

---

### Commitlint

[commitlint](https://github.com/conventional-changelog/commitlint) checks if your commit messages meet the [conventional commit format](https://conventionalcommits.org).

**Configuration file**: ```.commitlintrc```.

In general the pattern mostly looks like this:
```sh
type(scope?): subject  #scope is optional
```
Are you a good `commitizen` ?

---

### ESLint

[ESLint](https://eslint.org/) is a fully pluggable tool for identifying and reporting on patterns in JavaScript.

**Configuration file**: ```.eslintrc```.

For more configuration options and details, see the [configuration docs](https://eslint.org/docs/user-guide/configuring).

---

### GitHub Actions

[GitHub Actions](https://github.com/features/actions) makes it easy to automate all your software workflows, now with world-class CI/CD. Build, test, and deploy your code right from GitHub. Make code reviews, branch management, and issue triaging work the way you want.

**CI workflow file**: [```.github/workflows/ci.yml```](https://github.com/smarlhens/ng8-boilerplate/blob/master/.github/workflows/ci.yml).

---

### Husky

[Husky](https://github.com/typicode/husky) is a package that helps you create Git hooks easily.

**Configuration file**: ```.huskyrc```.

---

### Lint-staged

[Lint-staged](https://github.com/okonet/lint-staged) is a Node.js script that allows you to run arbitrary scripts against currently staged files.

**Configuration file**: ```.lintstagedrc```.

---

### Prettier

[Prettier](https://prettier.io/) is an opinionated code formatter.

**Configuration file**: ```.prettierrc```.

For more configuration options and details, see the [configuration docs](https://prettier.io/docs/en/configuration.html).

---

### Stylelint

[Stylelint](https://stylelint.io/) is a mighty & modern style linter.

**Configuration file**: ```.stylelintrc```.

---

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

---

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

---

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

---

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

---

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

---

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

---
