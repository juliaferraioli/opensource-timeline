# Open source timeline
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

The open source timeline aims to collect events and periods within open source history in a machine-readable format (comma separated value).

## Schema

Each entry in the timeline should have the following information:

- `start`, date in the format YYYY-MM-DD, YYYY-MM, or YYYY
- `end`, date in the format YYYY-MM-DD, YYYY-MM, or YYYY (optional; primarily used for periods)
- `title`, ideally a short string
- `description`, 1-3 sentences with more information
- `eventType`, using one of the following strings:
  - `release`, for events such as UNIX's fourth edition which was rewritten in `C` or the introduction of `git`
  - `vulnerability`, for events such as Heartbleed or Log4shell
  - `milestone`, for events such as Linux breaking 3% of market share for desktop in 2020 or the founding of the Open Source Initiative (OSI)
  - `other`, for events that don't fit into any of the above categories; please add tags if you use this `eventType`
- `eventImportance`, using one of the following strings:
  - `note`, for events that are more commentary or tangentially related to open source events
  - `low`, for minor events
  - `medium`, for normal-ish level events
  - `high`, for events that had a major impact on open source
  - `critical`, for events that had an impact beyond the open source ecosystem
- `referenceURI`, a link that acts as a citation for the event
- `imageURI`, a link to an image that represents the event (optional)
- `mediaURIs`, a list of links that provide additional context (optional)
- `tags`, a list of keywords that add context (optional)

The official schema is captured in [schema.json](schema.json), which is enforced when adding new entries to the timeline.

## Contributing

Please see the instructions in [CONTRIBUTING.md](CONTRIBUTING.md).

## Maintainer(s)

This timeline is maintained by [julia ferraioli](https://github.com/juliaferraioli) who is perpetually oversubscribed. Patience is appreciated!

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://shanecurcuru.org/"><img src="https://avatars.githubusercontent.com/u/1765681?v=4?s=100" width="100px;" alt="Shane Curcuru"/><br /><sub><b>Shane Curcuru</b></sub></a><br /><a href="#research-ShaneCurcuru" title="Research">🔬</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## License

This repository is licensed under [CC0 1.0 Universal](LICENSE).
