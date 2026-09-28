wmas-diff
=========

This repo is used to help generate visual diffs between [WMAS](https://github.com/w3c/webmediaapi) versions.

Manual steps I do every year, based on [PR Preview](https://github.com/tobie/pr-preview):

- Take the current, approved index.html file and run it through [Spec Generator](https://www.w3.org/publications/spec-generator/) to generate the ReSpec HTML
- Add that file to this repo
- Use the public URL of the respec HTML file and the previous year's respec HTML file to generate a diff through https://services.w3.org/htmldiff
