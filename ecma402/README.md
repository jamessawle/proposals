# [ECMAScript Internationalization API Specification](https://github.com/tc39/ecma402) proposals

 - [Stage 0 Proposals](stage-0-proposals.md)
 - [Finished Proposals](finished-proposals.md)

 [ECMAScript](../README.md) proposals

## Active proposals

Proposals follow [this process document](https://tc39.github.io/process-document/).
This list contains only stage 1 proposals and higher that have not yet been withdrawn/rejected, or become finished.

### Stage 3

| Proposal                                                               | Author                           | Champion                         | TC39 meeting notes                                    |
| ---------------------------------------------------------------------- | -------------------------------- | -------------------------------- | ----------------------------------------------------- |
| [`Intl.ListFormat`][intl.listformat]                                   | Zibi Braniecki                   | Zibi Braniecki                   |                                                       |
| [`Intl.Locale`][intl.locale]                                           | Zibi Braniecki, Daniel Ehrenberg | Zibi Braniecki, Daniel Ehrenberg |                                                       |
| [Intl.NumberFormat Unified API Proposal][numberformat]                 | Shane Carr                       | Shane Carr                       |                                                       |
| [`DateTimeFormat` `dateStyle` & `timeStyle`][datetimeformat]           | Zibi Braniecki                   | Zibi Braniecki                   | [March&nbsp;2019][datetimeformat-notes]               |
| [`Intl.DateFormat.prototype.formatRange`][formatrange]                 | Felipe Balbontín                 | Sathya Gunasekaran               | [March&nbsp;2019][formatrange-notes]                  |
| [Intl.DisplayNames][proposal-intl-displaynames]                        | Frank Tang                       | Frank Tang                       | [October&nbsp;2019][proposal-intl-displaynames-notes] |

### Stage 2

| Proposal                                                     | Author                           | Champion                                                       |
| ------------------------------------------------------------ | -------------------------------- | -------------------------------------------------------------- |
| [`Intl.Segmenter`: Unicode Segmentation in JavaScript][intl-segmenter] | Daniel Ehrenberg and Richard Gibson       | Richard Gibson                                               |

### Stage 1

| Proposal                                                     | Author         | Champion       |  <sub>Last Presented</sub>                                        |
| ------------------------------------------------------------ | -------------- | -------------- | ----------------------------------------------------------------- |

### Contributing new proposals

Please see [Contributing to ECMAScript](https://github.com/tc39/ecma262/blob/master/CONTRIBUTING.md) for the most up-to-date information on contributing proposals to this standard.

### Onboarding existing proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal that lives outside the TC39 organization:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
  - if you are a TC39 delegate, but not an admin in that organization, please contact [@LJHarb](https://github.com/ljharb)
2. [@bterlson](https://github.com/bterlson), [@gesa](https://github.com/gesa), or [@codehag](https://github.com/codehag) will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work **as long as** you never create a fork, or a new repository, with the same name - although Github Pages redirects will be broken (please update your links!).

[intl-segmenter]: https://github.com/tc39/proposal-intl-segmenter
[intl.listformat]: https://github.com/tc39/proposal-intl-list-format
[datetimeformat]: https://github.com/tc39/proposal-intl-datetime-style
[datetimeformat-notes]: https://github.com/tc39/notes/blob/master/meetings/2019-03/mar-26.md#datestyletimestyle-for-stage-3
[intl.locale]: https://github.com/tc39/proposal-intl-locale
[formatrange]: https://github.com/tc39/proposal-intl-DateTimeFormat-formatRange
[formatrange-notes]: https://github.com/tc39/notes/blob/master/meetings/2019-03/mar-26.md#intldatetimeformatprototypeformatrange-for-stage-3
[numberformat]: https://github.com/tc39/proposal-unified-intl-numberformat
[proposal-intl-displaynames]: https://github.com/tc39/proposal-intl-displaynames
[proposal-intl-displaynames-notes]: https://github.com/tc39/notes/blob/master/meetings/2019-10/october-2.md#intldisplaynames
