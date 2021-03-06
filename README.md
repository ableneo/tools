[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)
[![Build Status](https://travis-ci.org/ableneo/modules.svg?branch=master)](https://travis-ci.org/ableneo/modules)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![dependency](https://david-dm.org/ableneo/modules/status.svg)](https://david-dm.org/ableneo/modules)
[![devDep](https://david-dm.org/ableneo/modules/dev-status.svg)](https://david-dm.org/ableneo/modules?type=dev)
[![Known Vulnerabilities](https://snyk.io/test/github/ableneo/modules/badge.svg)](https://snyk.io/test/github/ableneo/modules)
[![tested with jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://github.com/facebook/jest)
[![use typescript](https://img.shields.io/badge/use-typescript-blue.svg)](https://www.typescriptlang.org/)

# @ableneo/modules

Javascript Modules monorepo with publishing to https://www.npmjs.com/~ableneo

This repo contains packages used at @ableneo with shared configuration for JavaScript/TypeScript tooling.

### - [`eslint-config-ableneo`](./packages/eslint-config-ableneo/) - ESLint configuration with support for TypeScript, Flow and Prettier integration.

### - [`@ableneo/prettier-config`](./packages/prettier-config/) - Prettier configuration file.

## How to develop

Open terminal in root of the project and run following command that will start styleguide server `docz` and run watch builds and tests.

```bash
yarn run dev
```

If you just want `docz` styleguide then run just

```bash
yarn run docz:dev
```

## Generating new packages

Npm script will prompt name of the package and generate boilerplate.

```bash
yarn generate:package
```

## Use Conventional Commits

- https://www.conventionalcommits.org

The commit message should be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

The commit contains the following structural elements, to communicate intent to the consumers of your library:

1._fix_: a commit of the type fix patches a bug in your codebase (this correlates with PATCH in semantic versioning).

2._feat_: a commit of the type feat introduces a new feature to the codebase (this correlates with MINOR in semantic versioning).

3._BREAKING CHANGE_: a commit that has the text BREAKING CHANGE: at the beginning of its optional body or footer section introduces a breaking API change (correlating with MAJOR in semantic versioning). A BREAKING CHANGE can be part of commits of any type.

- Others: commit types other than fix: and feat: are allowed, for example @commitlint/config-conventional (based on the the Angular convention) recommends _chore:, docs:, style:, refactor:, perf:, test:_, and others.

## Releasing new version

Code that is merged to `master` will be automatically released by the `travis-ci` pipeline. New version will be determined by the commit names.

# About Ableneo

![Twitter Follow](https://img.shields.io/twitter/follow/ableneo1.svg?label=Ableneo&style=social)

##### Read our blog

- https://medium.com/ableneo
- https://www.ableneo.com/blog

##### Our website

- https://www.ableneo.com/

##### Contact us

- [+421 2 32 144 791](tel:+421232144791)
- [info@ableneo.com](mailto:info@ableneo.com?subject=Subject%20|%20contact%20from%20github)

## Maintainers

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/marcelmokos">
          <img width="150" height="150" src="https://github.com/marcelmokos.png?v=3&s=150"/>
          <br></br>
          Marcel Mokoš
        </a>
        <div>
          <a href="https://twitter.com/marcelmokos">
            <img src="https://img.shields.io/twitter/follow/marcelmokos.svg?style=social&label=Follow" />
          </a>
        </div>
      </td>
    </tr>
  </tbody>
</table>

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://github.com/marcelmokos"><img src="https://avatars2.githubusercontent.com/u/6388074" width="100px;" alt="Marcel Mokos"/><br /><sub><b>Marcel Mokos</b></sub></a><br /><a href="https://github.com/ableneo/modules/commits?author=marcelmokos" title="Code">💻</a> <a href="https://github.com/ableneo/modules/commits?author=marcelmokos" title="Documentation">📖</a> <a href="https://github.com/ableneo/modules/issues?q=author%3Amarcelmokos" title="Bug reports">🐛</a> <a href="#review-marcelmokos" title="Reviewed Pull Requests">👀</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->
