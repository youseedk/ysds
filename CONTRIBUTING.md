# How to contribute

## Reporting issues
Should you run into any issues with the documentation site, or npm package, please don't hesitate to let us know by filling an [issue](https://github.com/youseedk/dna/issues/new).
It is important that the issue is well described and a screenshot is added. Also, if you are filling in a bug please remember to add your browser version and steps in how to reproduce the issue.
Please don't assign anybody to the task. The contributors will automatically get a notification when your issue is created and will assign themselve when they have time to work on the issue.

## Branching strategy
We use [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow). This means instead of a single master branch, this workflow uses two branches to record the history of the project. The `master` branch stores the official releases, and the `develop` branch serves as an integration branch for features.
This means features and bugs branches should be created off and to the `develop` branch.

## Pull Requests
Please fork our [repository](https://github.com/youseedk/dna/) and create a pull request with your changes.

Generally we like to see pull requests that:
- Maintain the existing code style
- Are focused on a single change (i.e. avoid large refactoring or style adjustments in untouched code if not the primary goal of the pull request)
- Have good commit messages that describe what you do (and not what you have done). Also, you can add `- fixes #xxx` in the end of your PR. This will automatically close your issue #xxx (e.g. #192) under issues when your code is released. 

## Instructions to spin up the site in your browser
Please run:
- `npm ci`
- `npm i -g gulp` (only if you don't already have gulp installed)
- `gulp`

## Running tests
We don't have automatic tests except Travis CI testing the build. However, if you add a new component to the site or make severe changes to an exsiting one we require that you test it in all our [supported browsers](/docs/code-guidelines/browser-support). 

## Updating the NPM package and version number
This will be handled by somebody else when merging/deploying code to master/producton.
We use `semver` for versioning. Basically, we have to decide if the code changes in the develop branch is a patch, minor or major update.

## Releasing the latest version
This will be handled by somebody else when merging/deploying code to master/producton.

## Current contributors
<div class="contributors">
    <p>See a <a href="https://github.com/youseedk/dna/graphs/contributors">complete list of contributors</a> on GitHub.</p>
</div>
