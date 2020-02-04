# Testing Automatic Releases

This repo is a test to figure out how to automatically create releases on github using release notes
coming from a PR.

The release flow I usually follow privately and at work is:

- Merge feature branch into develop
- Bump the version in develop (semantic versioning major.minor.patch)
- Merge develop into master
- Create a release from master using the right version number
