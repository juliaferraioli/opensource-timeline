# Contributing to the open source timeline

Please send us your contributions!

## Adding a new event

_Before adding a new event, make sure that it is not already in the timeline._

When adding a new event, gather the information requested by the [schema](README.md#schema). You may omit the optional elements, but take care to keep the placeholder commas in the row. To validate your addition, you can use [csvlint](https://csvlint.io/) along with the [schema.json](schema.json) file (this is enforced at pull request time, but validating it first prevents a lot of back and forth on PRs).

You do not need to create an issue to add an event, but please make sure your sources are trustworthy.

If you are uncertain if an event should be included in the timeline, please open an issue to discuss it.

## Submitting pull requests

We follow the [standard GitHub fork-change-pull request model](https://docs.github.com/en/get-started/quickstart/contributing-to-projects). Make your changes in a fork of this repository and submit your changes in a pull request.

We're not fussy about the pull request title. Just keep it simple, such as:

> Add new event for the release of `git`

or

> Update `git` entry tags

We may ask you to make stylistic or grammatical changes in the interest of clarity and consistency.

After a PR is merged, the timeline will be automatically sorted by the `start` field.

## Note

**An opened pull request does not mean that we will merge it into the timeline.**

There are events that we may consider irrelevant or too minor to include in the timeline. There aren't any hard and fast rules for this; it is up to the maintainers to make this judgement call.
