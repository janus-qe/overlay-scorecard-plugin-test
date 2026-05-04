# overlay-scorecard-plugin-test

This repository contains fixtures for end-to-end tests related to the scorecard plugin.

> **Note:** This README is present for the purpose of the filecheck e2e test for the filecheck scorecard backend module.

## Files

- **`all-scorecards.yaml`** — A Backstage component definition that has both GitHub and Jira scorecards configured.
- **`github-scorecard-only.yaml`** — A Backstage component definition that has only a GitHub scorecard configured.
- **`jira-scorecard-only.yaml`** — A Backstage component definition that has only a Jira scorecard configured.
- **`openssf-scorecard-only.yaml`** — A Backstage component definition that has only an OpenSSF scorecard configured.
- **`no-scorecards.yaml`** — A Backstage component definition with no scorecards attached.
- **`invalid-threshold.yaml`** — A Backstage component definition used to test behaviour when a scorecard threshold is invalid.
- **`metrics-unavailable.yaml`** — A Backstage component definition used to test behaviour when scorecard metrics are unavailable.
- **`addon-test.yaml`** — A Backstage component definition used to test scorecard addon functionality.
