# ACCESS-Hive
[![ACCESS-Hive Badge](docs/assets/badge.svg)](https://access-hive.org.au/)
[![github-contributors](https://img.shields.io/github/contributors/ACCESS-Hive/access-hive.github.io?color=blue&style=plastic)][github-repo]
[![forum-users](https://img.shields.io/discourse/users?color=blue&label=forum&server=https%3A%2F%2Fforum.access-hive.org.au&style=plastic)][forum]
[![Link Check](https://github.com/ACCESS-Hive/access-hive.github.io/actions/workflows/scheduled_link_check.yml/badge.svg)](https://github.com/ACCESS-Hive/access-hive.github.io/actions/workflows/scheduled_link_check.yml)

Documentation hub for the Earth System models, ACCESS, and their community.

This repository uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to build the website which accessible at this URL:

https://access-hive.org.au/

If you wish to add documentation to the ACCESS-Hive website see the [contribution guide](https://access-hive.org.au/about/contribute/) for instructions.

# How to Contribute [Draft]

- Pull the latest version of `development` branch locally by using the following commands:

    `git fetch`    > Fetch all remote branches from github
 
    `git switch development`     > Switch to the `development` branch

    `git pull`      > Pull latest remote changes on the `development` branch locally 

- If using VSCode, make sure the `development` branch is currently selected at the bottom right branch tab.

![Screenshot 2023-07-28 at 10 14 39 am](https://github.com/ACCESS-Hive/access-hive.github.io/assets/42607679/aa1c5281-2298-41d6-8ac1-adc478d72a58)

- Create a branch from the `development` branch of ACCESS-HIVE repo, for instance, `dev/jasmeen/legacy-release`. 

- Use the following two commands to create a new branch and push it to github respectively:

    `git checkout -b dev/jasmeen/legacy-release`

    `git push --set-upstream origin dev/jasmeen/legacy-release`

- Prefixing the branch name with `dev/jasmeen` might be used as an indicator that this needs to merged in the `development` branch of access-hive (staging branch deployed on https://access-hive.org.au/development_site/), and _**not**_ the main branch.

- Work locally on the branch `dev/jasmeen/legacy-release`, and push the commits using the commands: 

    `git add .`

    `git commit -m "First commit"`

    `git push`
  
- While working locally on the branch, please make sure to regularly pull the changes from the `development` branch into your branch, using the command:

    `git pull origin development`

  This would make sure that the local branch `dev/jasmeen/legacy-release` is always in sync with the `development` branch, which is updated with PRs regularly. 

- Once the changes on the local branch `dev/jasmeen/legacy-release` is ready to be integrated with the `development` branch, create a pull request on github by changing the `base` to `development`. (Please find the below screenshot). This would create a pr on the `development` branch.

![Screenshot 2023-06-02 at 2 05 13 pm](https://github.com/ACCESS-Hive/access-hive.github.io/assets/42607679/ec141fc9-ee00-4a84-ae5a-081761400765)

# License
The ACCESS-Hive site is covered by [the CC-BY 4.0 license][License].

However, the material linked to from ACCESS-Hive is covered by various licensing agreements. Our users should directly refer to the terms and conditions of any material they are using to understand their rights and responsibilities.

[License]: License.md
[github-repo]: https://github.com/ACCESS-Hive/access-hive.github.io.git
[forum]: https://forum.access-hive.org.au
