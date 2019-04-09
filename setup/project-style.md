## Overview:

This issue is intended to document for our current processes within this project. Once everyone agrees on the document, contents should only be changed once discussed with and agreed by the whole team.

## Contents:

- [Linting](#Linting)
- [Naming Branches](#Naming-Branches)
- [Commit messages](#Commit-Messages)
- [Pull Request Checklist](#Pull-Request-Checklist)
- [Merging Pull Requests](#Merging-Pull-Requests)

## Linting

- To begin with, we would suggest using eslint with the airbnb style guide configuration for easy setup (to be done on one computer and added to project file)
- Further edits to the linter configuration file can be discussed, agreed on, and documented here.

## Naming Branches

- feature/fix convention
  - E.g. `feature/add-search-function` or `fix/change-searchbar-color`

## Commit Messages

- Should include issue #
- Written with 'imperative tone' to describe what a commit does, rather than what it did.
  - E.g. `Change color of search bar` instead of `Changed/changes color of search bar`

## Pre Pull Request Checklist

- [ ] **Branch is up to date with master**
- [ ] **The project runs**
- - [ ] You can download and install locally, and run the project locally
- - [ ] All existing and new features run without bugs
- - [ ] The build script runs without error
- - [ ] (If the project is already deployed to Heroku) the branch to be merged can deploy successfully to Heroku
- [ ] **Code is consistent**
- - [ ] Linter is used, no error messages
- - [ ] Code is consistent with agreed team style
- - [ ] Naming of files is consistent with project (e.g. all files named with camelCase)
- [ ] **Tests are in place**
- - [ ] Test file is in the same folder as the original file, with the extension .test.js
- - [ ] Each new file written has a test file (where possible)
- [ ] **Tests all pass**
- - [ ] All tests should pass locally and on Travis
- - [ ] Edge cases have been considered in tests
- [ ] **Test coverage is maintained**
- - [ ] Project coverage stays > 95%
- - [ ] PR will not bring down coverage by more than 1%
- - [ ] Files and lines of code have been ignored if they cannot be tested
- - [ ] If you are stuck with writing tests, you have assigned @arrested-developer to the PR and added a comment to explain what help is needed
- [ ] **No console logs**
- - [ ] Console.log is only used for crucial system messages (e.g. which port server is on).
- - [ ] Any console.logs used for debugging have been removed.
- - [ ] Console.error is used in error handling.
- - [ ] global.console.log and global.console.error are mocked in tests when needed to avoid littering the console

## Merging Pull Requests

- The person that made the pull request is responsible for the final merge, but only after someone else from the team has reviewed, approved, and left a comment on the pull request to that affect
