# Contribution guidelines

## Table of Contents

- [Getting started](#getting-started)
  - [Language](#language)
    - [For native English speakers](#for-native-english-speakers)
  - [Code of Conduct](#code-of-conduct)
- [How can I help?](#how-can-i-help)
  - [Documentation](#documentation)
  - [Issues](#issues)
    - [Submitting an issue](#submitting-an-issue)
  - [Feedback](#feedback)
  - [Code](#code)
    - [Dev environment](#dev-environment)
- [Commiting](#commiting)
  - [Skipping building process](#skipping-building-process)
  - [Why all these rules?](#why-all-these-rules)
- [Submitting a pull request](#submitting-a-pull-request)

## Getting started

First off, we would like to thank you for taking the time to contribute and make this a better project!

Here we have a set of instructions and guidelines to reduce misunderstandings and make the process of contributing to `angular-query` as smooth as possible.

We hope this guide makes the contribution process clear and answers any questions you may have.

### Language

Please, while contributing or interacting in any way in this project, refrain from using any language other than **English**.

#### For native English speakers

Try to use simple words and sentences. Don't make fun of non-native English speakers if you find something wrong about the way they express themselves.

Try to encourage newcomers to express their opinions, and make them comfortable enough to do so.

### Code of Conduct

We expect that project participants to adhere to our Code of Conduct. You can check the [full text](CODE_OF_CONDUCT.md) so that you may understand the kind of conduct we are expecting and what actions will and will not be tolerated.

By participating in this project, you agree to abide by its terms.

## How can I help?

Here are some ways you can help along with some guidelines.

### Documentation

As a user of `angular-query`, you're the perfect candidate to help us improve our documentation!

Typos, errors, lack of examples and/or explanation and so on, are just some examples of things that could be fixed and/or improved.

You could even make improvements to this guide! :)

While documenting, try to keep things simple and clear.

### Issues

Some issues are created with missing information, without a template, not reproducible, or plain
invalid.

You can make them easier to understand and resolve.

#### Submitting an issue

- Please search for similar issues before opening a new one;
- Use one of the corresponding issue templates;
- Use a clear and descriptive title;
- Include as much information as possible by filling out the provided issue
  template;
- Most of the time, the best way to report an issue is a failing test proving it.

### Feedback

The more feedback the better! We're always looking for more suggestions and opinions on discussions. That's a good opportunity to influence the future direction of this tool.

This includes submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.


### Code

You can use issue labels to discover issues you could help out with:

- `bug` issues
  are known bugs we'd like to fix;
- `enhancement` issues
  are features we're open to include.

The
`help wanted`
and
`good first issue`
labels are especially useful.

When you see an issue that is already assigned, please check to see if there isn't someone working on it already (maybe try asking in the issue). This is to prevent unnecessary work for everyone involved.

#### Dev environment

When developing, prefer using **Node** ≥ 8 and **yarn**. Writing code with the latest stable Node versions allows us to use newer developer tools.

After [cloning the repository](https://help.github.com/articles/cloning-a-repository/), run `yarn` to install dependencies.

A summary of the scripts:

- To run the example use `yarn dev:example`;
- The `yarn dev:start` command will build the lib and watch files in bundle and rebuild on changes;
- Running `yarn dev` will run both `dev:example` and `dev:start`;
- Use `yarn test` to run the test suite (powered by [Jest](https://facebook.github.io/jest/));
  - For code coverage locally, you can run `yarn test --coverage`.
- `yarn build` will build the lib 


## Contribution guide

Please consider these guidelines when filing a pull request:

*  Commits follow the [Angular commit convention](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
*  JavaScript is written using ES2015 features
*  2 spaces indentation
*  Features and bug fixes should be covered by test cases

use the `yarn commit` command, follow the instructions and your commit will be performed

## Submitting a pull request

Before submitting a pull request, please make sure the following is done:

- [Fork](https://help.github.com/en/articles/fork-a-repo) the repository and create your branch from `main`.
  - Example: `feature/my-awesome-feature` or `fix/annoying-bug`;
- Run `yarn` in the repository root;
- If you’ve fixed a bug or added code that should be tested, **add tests**;
- Ensure the test suite passes;
- Ensure your commit is validated;
