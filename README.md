# Candlelight

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)][license]
[![](https://img.shields.io/badge/Author-The%20Glow%20Getters-ff69b4.svg)](https://twitter.com/TheGlowGetters)

This repository contains the source code for [Candlelight][candlelight] which
was developed for the [Space Apps COVID-19
Challenge](https://covid19.spaceappschallenge.org/). Religious festivals are an
incredibly important times for millions of people around world. The celebration
period of many festivals during 2020 occurs during the COVID-19 pandemic.
[Candlelight][candlelight] is designed for the monitoring and prediction of
impacts of religious festivals during the COVID-19 pandemic.

## Development

For every new task that requires additional commentary or will produce resources
like new figures you should first create a [new issue][new-issue] to track it's
progress.

If there are resources associated with this issue (such as figures or data
files) create a new subfolder in the folder `/issues` after having
[created the issue][new-issue] on GitHub. For example
`/issues/5-some-time-domain-plot`. Make sure to include the issue number at the
beginning of the folder name. Optionally add a short dash case qualifier tag to
the end to make it quick and easy for others to know what the resources are for.

When you commit resources make sure to include `#<issue-number>` at the end of
the first line of your commit message. This will then associated that commit
with the issue, it will show up in the history of the issue making it easier
to find resources and help when reading through the commit history. For example
`Add new figure #5`.

## Licence

[`candlelight`][candlelight] is released under the [MIT license][license].

[candlelight]: https://github.com/Galadirith/candlelight
[license]: LICENSE.md
[new-issue]: https://github.com/Galadirith/candlelight/issues
