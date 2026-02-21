<img align="right" src="https://raw.github.com/cliffano/upgrade-deps-action/main/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/upgrade-deps-action/workflows/CI/badge.svg)](https://github.com/cliffano/upgrade-deps-action/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/upgrade-deps-action/badge.svg)](https://snyk.io/test/github/cliffano/upgrade-deps-action)
<br/>

Upgrade Deps Action
-------------------

GitHub Action for creating a repository release using [Renovate](https://github.com/cliffano/rtk).

Usage
-----

Upgrade the dependencies:

    jobs:
      build:
        steps:
          - uses: cliffano/upgrade-deps-action@main
            with:
              type: 'major'

The type value can be one of `major`, `minor`, or `patch`.
