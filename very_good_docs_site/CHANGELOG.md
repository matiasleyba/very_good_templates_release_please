## 1.0.0

refactor(very_good_docs_site)!: remove root-level project_name folder from brick structure.

### Migration details

The `very_good_docs_site` brick no longer includes a top-level project name folder.
This allows generating the project directly into the current or a custom directory.

If you prefer to keep the output inside its own folder (as before), use the -o flag:

```dart
// Before:
mason make very_good_docs_site

// After:
mason make very_good_docs_site -o ./output_folder
```

## [1.1.0](https://github.com/matiasleyba/very_good_templates_release_please/compare/very_good_docs_site-v1.0.0...very_good_docs_site-v1.1.0) (2025-08-05)


### Features

* setup missing templates ([3e4b5b1](https://github.com/matiasleyba/very_good_templates_release_please/commit/3e4b5b17dd84680325fcd4ecdd3bc5de72a55cd2))


### Docs

* format changelogs ([f260ce4](https://github.com/matiasleyba/very_good_templates_release_please/commit/f260ce4395b17f452a72fe0ae09dc70390bc3a14))

## 0.0.5

- fix: evaluate brick output correctly on ci [#248](https://github.com/VeryGoodOpenSource/very_good_templates/pull/248)

## 0.0.4

- feat: update pull request templates to add `test` type option ([#214](https://github.com/VeryGoodOpenSource/very_good_templates/pull/214))
- chore(deps-dev): bump @docusaurus/module-type-aliases from 3.3.2 to 3.4.0 in /very_good_docs_site/**brick**/{{project_name.snakeCase()}} ([#118](https://github.com/VeryGoodOpenSource/very_good_templates/pull/118))
- chore(deps-dev): bump eslint from 8.57.0 to 9.2.0 in /very_good_docs_site/**brick**/{{project_name.snakeCase()}} ([#94](https://github.com/VeryGoodOpenSource/very_good_templates/pull/94))
- chore(deps-dev): bump @docusaurus/module-type-aliases from 3.4.0 to 3.5.2 in /very_good_docs_site/**brick**/{{project_name.snakeCase()}} ([#175](https://github.com/VeryGoodOpenSource/very_good_templates/pull/175))
- chore(deps-dev): bump @docusaurus/module-type-aliases from 3.5.2 to 3.6.0 in /very_good_docs_site/**brick**/{{project_name.snakeCase()}} ([#212](https://github.com/VeryGoodOpenSource/very_good_templates/pull/212))

## 0.0.3

- chore: migrate very_good_docs_site ([#6](https://github.com/VeryGoodOpenSource/very_good_templates/pull/6))
- chore: update bricks to Mason 0.1.0-dev.52 ([#28](https://github.com/VeryGoodOpenSource/very_good_templates/pull/28))

## 0.0.2

- build(deps-dev): bump @tsconfig/docusaurus in /src/very_good_docs_site ([#135](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/135))
- chore: generate template ([#136](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/136))
- build(deps): bump @docusaurus/core in /src/very_good_docs_site ([#140](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/140))
- build(deps): bump @docusaurus/preset-classic in /src/very_good_docs_site ([#137](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/137))
- build(deps): bump actions/setup-node from 3 to 4 ([#145](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/145))
- chore: request code ownership ([#147](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/147))
- feat: update to docusaurs 3.0 ([#152](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/152))
- refactor: remove generator script ([#162](https://github.com/VeryGoodOpenSource/very_good_docs_site/pull/162))

## 0.0.1+7

- build(deps): various dependency updates

## 0.0.1+6

- build(deps): various dependency updates

## 0.0.1+5

- build(deps): various dependency updates

## 0.0.1+4

- build(deps): various dependency updates

## 0.0.1+3

- build(deps): upgrade to docusaurus 2.2.0

## 0.0.1+2

- refactor: use npm

## 0.0.1+1

- build(deps): upgrade lockfile

## 0.0.1

- feat: initial release 🎉
