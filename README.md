
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hearthstone: tools for competitive HearthstoneⓇ players

<!-- badges: start -->

<!-- badges: end -->

hearthstone package is designed to help competitive Hearthstone players
to make optimal decisions when playing in tournaments. In particular, it
offers tools (R functions, vignettes and Shiny apps) for finding subgame
perfect Nash equilibria in mixed strategies for the following
competitive formats: Conquest, Shield-Phase Conquest, Last Hero
Standing, Specialist and Strike.

## Installation

You can install the latest version of hearthstone with:

``` r
install.packages("devtools")
devtools::install_github("naturewillconfess/hearthstone")
```

## What’s included in this pre-alpha version

  - [Vignettes](https://github.com/naturewillconfess/hearthstone/tree/master/vignettes)
    on Strike, Specialist and Conquest. Check them out\!
  - R functions
      - `strike_nash()` for calculating Strike winrate (trivial)
      - `spec_nash()` for determining Nash equilibrial strategy and
        winrates in Specialist format
      - `conquest_nash()` and `conquest_nash_short()` for determining
        Nash equilibrial strategy and winrates in Conquest
      - `LHS_nash()` for determining Nash equilibrial strategy and
        winrates in LHS
      - `ban_nash()` for determining Nash equilibrial bans in Conquest
        ban phase
      - `shield_nash()` for determining Nash equilibrial shields in
        Conquest shield phase
  - Shiny apps - `strike_run_app()`and `specialist_run_app()`

## News

Version 0.2.0 is here\! Most functions should work now, and basic unit
tests are in place. Structure of the output can still change - I want to
make output of higher-level functions a bit more user-friendly.

## Future plans

  - LHS and Conquest Shiny apps
  - LHS vignette
  - Nash equilibrial ladder strategy
  - Format-specific line-up composers

## Legal disclaimer

Hearthstone is a trademark or registered trademark of Blizzard
Entertainment, Inc., in the U.S. and/or other countries. I’m not
affiliated with Blizzard Entertainment, Inc. in any way.
