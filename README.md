# CMDS Platform

Open-source platform for _[short tagline to be completed]_.

This repository is the monorepo for CMDS. It contains the API, libraries, web application, extensions, integrations, infrastructure, and documentation for the platform.

## Repository layout

Root folders follow a fixed convention:

| Folder   | Purpose |
| :------- | :------ |
| `build`  | Build configuration, scripts, and tooling |
| `config` | Project configuration and environment settings |
| `data`   | Reference datasets, fixtures, and bundled data |
| `db`     | Database schema (DDL), migrations, and seed data |
| `dist`   | Build output artifacts (gitignored) |
| `docs`   | Project documentation (MkDocs Material, published via GitHub Pages) |
| `infra`  | Deployment configuration and operational tooling |
| `public` | Static web-visible resources |
| `src`    | Application source code, organized by `api`, `cli`, `lib`, `web` |

Under `src/web/`, the `lobby` application hosts the unauthenticated user surface — components, services, and workflows accessible without authentication.

Test projects live next to the code they cover, following the .NET sibling convention: `src/Foo/` has `src/Foo.Tests/` alongside it.

## Prerequisites

_To be completed: .NET SDK version, Node.js version (if used for web/docs tooling), database engine and version, any other required tooling._

## Build and run

_To be completed: clone, restore, build, run, and test commands._

## Documentation

Full documentation lives under [`docs/`](docs/) and is published at _[URL to be completed]_.

## Contributing

Contribution guidelines live in the [cmds-app/.github](https://github.com/cmds-app/.github) repository and apply to every CMDS project.

## License

_To be completed._
