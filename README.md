# API-Public
Publicly Visible Maknae API

## Follow Best Practice:
* https://github.com/zhanymkanov/fastapi-best-practices


## Creating a New Pull Request
* If these are a Work In Progress (WIP) create a draft PR.
* Issue number might not exist if feature or bug has come internally, drop the `<issue-number>` if this is the case.
* We use three branch types, feature and bug should be on separate branches, hotfix is for main/master:
  * Feature Branches
  * Bug Branches
  * Hotfix Branches 

### Convention into Main Branch
* Bug Fixes: `hotfix/<issue-number>/<hotfix-name>`
  * E.g.: `hotfix/1471/handle-idol-not-exist-error`
  * E.g.: `hotfix/handle-idol-not-exist-error`

### Convention into Release Branch
* Fix: `bugfix/<release-branch>/<issue-number>/<bugfix-name>`
  * E.g.: `bugfix/v1.3/1471/bias-stops-halfway`
  * E.g.: `bugfix/v1.3/bias-stops-halfway`

### Convention into Feature Branch
* Fix: `bugfix/<release-branch>/<feature-area>/<issue-number>/<bugfix-name>`
  * E.g.: `bugfix/v1.3/idol-bias/1471/bias-stops-halfway`
  * E.g.: `bugfix/v1.3/idol-bias/bias-stops-halfway`
* Feature: `feature/<release-branch>/<feature-area>/<issue-number>/<feature-name>`
  * E.g.: `feature/v1.3/idol-bias/1471/add-random-bias-selection`
  * E.g.: `feature/v1.3/idol-bias/add-random-bias-selection`


## Commenting Code
* From time to time we know an approach could be better or will need to be re-written, this is why the todo exist. In addition to the use of todo as comment prefix's please use these when applicable.
  * // Todo: <todo-message>
  * // Issue: <issue-message>
  * // Future: <future-change-message>