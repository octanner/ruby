# Style Guide

## Guide

> We follow the [Ruby Community Style Guide](https://github.com/bbatsov/ruby-style-guide)

Uniformity allows us to onboard developers and move across teams with ease.

## Tooling

> [Rubocop](https://github.com/bbatsov/rubocop) helps ensure adherence for our ruby code and [Rubocop-RSpec](https://github.com/backus/rubocop-rspec) covers our tests.

We use tooling to make adherence easier.

Note that running `rubocop -a` will automatically fix most style violations

## Implementation

* We will implment rubocop on each CI for every team not fail
* auto ignore existing violations, tech debt
* Build a common ignore list our own style guide
