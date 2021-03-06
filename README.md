# netatmo-rs

[![Linux Build Status](https://circleci.com/gh/lukaspustina/netatmo-rs.svg?style=shield)](https://circleci.com/gh/lukaspustina/netatmo-rs) [![codecov](https://codecov.io/gh/lukaspustina/netatmo-rs/branch/master/graph/badge.svg)](https://codecov.io/gh/lukaspustina/netatmo-rs) [![GitHub release](https://img.shields.io/github/release/lukaspustina/netatmo-rs.svg)](https://github.com/lukaspustina/netatmo-rs/releases) [![](https://img.shields.io/crates/v/netatmo-rs.svg)](https://crates.io/crates/netatmo-rs) [![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg?label=License)](./LICENSE)

`netatmo-rs` is a simple [Rust](https://rust-lang.org) library to talk to [Netatmo's API](https://dev.netatmo.com/resources/technical/introduction).

## Changelog

Please see the [CHANGELOG](CHANGELOG.md) for a release history.


## Installation

### Create Netatmo App

1. Create a new App for your personal Netatmo account at the [Create an App](https://dev.netatmo.com/myaccount/createanapp) page.
2. Save client id and client secret.


## Development

### Run Examples

```bash
NETATMO_CLIENT_ID=xxxx NETATMO_CLIENT_SECRET=xxxx NETATMO_USERNAME=xxxx NETATMO_PASSWORD=xxxx NETATMO_DEVICE_ID=xxxx cargo run --example get_station_data
```

## Postcardware

You're free to use `netatmo-rs`. If you find it useful, I would highly appreciate you sending me a postcard from your hometown mentioning how you use `netatmo-rs`. My work address is

```
Lukas Pustina
CenterDevice GmbH
Rheinwerkallee 3
53227 Bonn
Germany
```

## Todos

1. Semantic transformation of results -> use enums, timezone etc instead of Strings and int values.

