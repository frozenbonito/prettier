# @unts/prettier

[![GitHub Actions](https://github.com/un-ts/prettier/workflows/Node%20CI/badge.svg)](https://github.com/un-ts/prettier/actions?query=workflow%3A%22Node+CI%22)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/un-ts/prettier.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/un-ts/prettier/context:javascript)
[![Codecov](https://img.shields.io/codecov/c/gh/un-ts/prettier)](https://codecov.io/gh/un-ts/prettier)
[![type-coverage](https://img.shields.io/badge/dynamic/json.svg?label=type-coverage&prefix=%E2%89%A5&suffix=%&query=$.typeCoverage.atLeast&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fun-ts%2Fprettier%2Fmaster%2Fpackage.json)](https://github.com/plantain-00/type-coverage)
[![GitHub release](https://img.shields.io/github/release/un-ts/prettier)](https://github.com/un-ts/prettier/releases)

[![Conventional Commits](https://img.shields.io/badge/conventional%20commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![Code Style: Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![changesets](https://img.shields.io/badge/maintained%20with-changesets-176de3.svg)](https://github.com/atlassian/changesets)

> Opinionated but Incredible Prettier plugins.

## Packages

This repository is a monorepo managed by [changesets][] what means we actually publish several packages to npm from same codebase, including:

| Package                                | Description                                                                                                                                                           | Version                                                                                                           |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [`prettier-plugin-pkg`](/packages/pkg) | An opinionated package.json formatter plugin for Prettier                                                                                                             | [![npm](https://img.shields.io/npm/v/prettier-plugin-pkg.svg)](https://www.npmjs.com/package/prettier-plugin-pkg) |
| [`prettier-plugin-sh`](/packages/sh)   | An opinionated `shellscript` formatter plugin for Prettier, also support simple format of `Dockerfile`, `properties`, `gitignore`, `dotenv`, `hosts`, `jvmoptions`... | [![npm](https://img.shields.io/npm/v/prettier-plugin-sh.svg)](https://www.npmjs.com/package/prettier-plugin-sh)   |
| [`prettier-plugin-sql`](/packages/sql) | An opinionated sql formatter plugin for Prettier                                                                                                                      | [![npm](https://img.shields.io/npm/v/prettier-plugin-sql.svg)](https://www.npmjs.com/package/prettier-plugin-sql) |

## Sponsors

| 1stG                                                                                                                               | RxTS                                                                                                                               | UnTS                                                                                                                               |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [![1stG Open Collective backers and sponsors](https://opencollective.com/1stG/organizations.svg)](https://opencollective.com/1stG) | [![RxTS Open Collective backers and sponsors](https://opencollective.com/rxts/organizations.svg)](https://opencollective.com/rxts) | [![UnTS Open Collective backers and sponsors](https://opencollective.com/unts/organizations.svg)](https://opencollective.com/unts) |

## Backers

| 1stG                                                                                                                             | RxTS                                                                                                                             | UnTS                                                                                                                             |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [![1stG Open Collective backers and sponsors](https://opencollective.com/1stG/individuals.svg)](https://opencollective.com/1stG) | [![RxTS Open Collective backers and sponsors](https://opencollective.com/rxts/individuals.svg)](https://opencollective.com/rxts) | [![UnTS Open Collective backers and sponsors](https://opencollective.com/unts/individuals.svg)](https://opencollective.com/unts) |

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](./CHANGELOG.md).

## License

[MIT][] © [JounQin][]@[1stG.me][]

[1stg.me]: https://www.1stg.me
[changesets]: https://github.com/atlassian/changesets
[jounqin]: https://github.com/JounQin
[mit]: http://opensource.org/licenses/MIT
