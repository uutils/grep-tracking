# Various tracking tools for grep

[![CI](https://github.com/uutils/grep-tracking/actions/workflows/gnu-data.yml/badge.svg)](https://github.com/uutils/grep-tracking/actions/workflows/gnu-data.yml)

Tracking the evolution of https://github.com/uutils/grep

## GNU testsuite comparison

Below is the evolution of how many GNU tests uutils/grep passes.

![GNU testsuite evolution](gnu-results.svg)

Refreshed twice a day by github actions. Changes are documented in the json file ([gnu-result.json](gnu-result.json)).

The workflow and the graph are shared with the other uutils tracking repositories, see [uutils-tracking](https://github.com/uutils/uutils-tracking).

Compares only the Linux execution.

Based on:
* https://github.com/uutils/grep/blob/main/util/run-gnu-testsuite.sh
