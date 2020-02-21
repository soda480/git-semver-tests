# git-semver-tests
Overview of git-semver functional tests

## Functional Tests

| Test |
| --- |
| git semver should return error when repository does not exist |
| init should display usage when invoked incorrectly |
| init should return error when specified version is not valid |
| init should set version when version is specified |
| init should set default version when no version is specified |
| git semver should return current version to stdout |
| bump pre with prefix should bump specified prefix |
| bump pre without prefix should bump default prefix pre |
| bump patch should bump patch level |
| bump minor should bump minor level |
| bump major should bump major level |
| bump final should bump to final level |
| tag should tag head with version |
| tag should fail if head is already tagged |
| push should push semver branch and tag to remote repository |
| removing .semver directory and execute init should pull down remote version |
| removing remote semver branch execute init should set default version |
