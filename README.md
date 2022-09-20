## Tournament Organizer
A Node.js module for organizing tournaments, written in TypeScript.

**Version 3 is now an ESM module.** If you don't understand what this means for you, [read this](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c).

[![npm](https://img.shields.io/npm/v/tournament-organizer?style=flat-square)](https://npmjs.org/package/tournament-organizer) [![GitHub last commit](https://img.shields.io/github/last-commit/slashinfty/tournament-organizer?style=flat-square)](https://github.com/slashinfty/tournament-organizer/commits/main) [![GitHub issues](https://img.shields.io/github/issues-raw/slashinfty/tournament-organizer?style=flat-square)](https://github.com/slashinfty/tournament-organizer/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/slashinfty/tournament-organizer?style=flat-square)](https://github.com/slashinfty/tournament-organizer/pulls) [![GitHub](https://img.shields.io/github/license/slashinfty/tournament-organizer?style=flat-square)](https://github.com/slashinfty/tournament-organizer/blob/main/LICENSE) [![Ko-Fi](https://img.shields.io/badge/Ko--Fi-Buy%20Me%20a%20Coffee-a87b00)](https://ko-fi.com/mattbraddock)

### About
This JavaScript module for Node.js facilitates the organization and execution of tournaments.

Tournaments can be paired by single elimination, double elimination, round-robin, double round-robin, and Swiss.

If round-robin, double round-robin, or Swiss are chosen, then a single elimination or double elimination playoffs can follow.

For non-elimination tournaments, the following tiebreakers systems are supported:
* Solkoff
* Median-Buchholz
* Sonneborn-Berger
* Cumulative
* Versus
* Opponent's match win percentage
* Game win percentage
* Opponent's game win percentage
* Opponent's opponent's match win percentage

### About Pairings
Details can be found in the [`tournament-pairings`](https://github.com/slashinfty/tournament-pairings) readme.

## Installation & Usage
```shell
npm i tournament-organizer
```

```ts
import TournamentOrganizer from 'tournament-organizer';

const Manager = new TournamentOrganizer();
```

## Contributing
Please submit an issue if you encounter a bug or have a feature suggestion.

If you are interested in contributing, please feel free to fork and clone the repository (on main branch), then submit a pull request.

I am a high school teacher, and would appreciate any and all support in continuing this project.