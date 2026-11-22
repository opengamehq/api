# opengame-api

Call the OpenGame creator API directly over HTTPS. Covers the base URL, creator tokens and scopes, the OpenAPI document, the error shape and retry fields, deploying without the CLI, and checking whether OpenGame is open.

It is one of the [OpenGame](https://opengame.io) agent skills, which teach a coding agent such
as Claude Code, Codex, Cursor or OpenCode to build a browser game and put it online.

## Install

```bash
npx skills add opengamehq/api
```

The skill installs under its own name, `opengame-api`. Every OpenGame skill, each under its own
name, installs from [opengamehq/opengame](https://github.com/opengamehq/opengame):

```bash
npx skills add opengamehq/opengame
```

How the skills fit into making and shipping a game is at [docs.opengame.io](https://docs.opengame.io).

## Changes

This is version 1.0.9. [CHANGELOG.md](CHANGELOG.md) lists what changed in each one.

## Issues

OpenGame's release tooling writes this repository from [opengamehq/opengame](https://github.com/opengamehq/opengame),
so a change made here is replaced by the next release, and it does not take pull requests.
Open an issue [there](https://github.com/opengamehq/opengame/issues) for a skill that teaches the wrong thing.

## License

[Apache 2.0](LICENSE).
