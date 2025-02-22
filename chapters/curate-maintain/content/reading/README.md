### Content

The content maintainer is responsible for overseeing different aspects of the open educational resource, like content management, accepting and reviewing contributions, or community building.

It is important for such a resource to clearly identify who the maintainer is, for the purpose of transparency and good communication.

The content is typically organized in a versioned system control repository such as `Git`, which has a series of advantages like version control, branching, history, etc.
It is also recommended using a managed development platform like `GitHub` or `GitLab`, which is built on top of `Git`, while also providing additional useful features, like code review, issues, pull requests, integrations, and others.

The content should be published under a license.
At `Open Education Hub` we employ the [`Creative Commons`](https://en.wikipedia.org/wiki/Creative_Commons_license) license ourselves and strongly recommend its usage.

#### Contributions

The content maintainer should foster a welcoming environment for outside contributions.
This can be achieved by:

- Establishing clear contribution guidelines (for example in a `CONTRIBUTING.md` file).
- Labeling issues with tags such as `help wanted` or `good first issue`, to help newcomers find tasks to contribute.
- Acknowledging the work of contributors (for example in the repository `README.md` file or in any other suitable place).

There should also be an established process for handling contributions whenever they arrive.
Some steps that the maintainer should take are:

- Review the contribution as soon as possible.

  Depending on the team size, this can be done by the maintainer, or it could be delegated to other members of the content development team.
  Tools like `GitHub` have features that can help with this: an issue can have a person designated as assignee, while a pull request can have one or multiple reviewers and assignees.
- Engage in a constructive discussion with the contributor to clarify any questions or concerns.
Provide feedback and guidance for improvement if the contribution needs changes.
- Ensure that the contribution follows the guidelines.
This can be partially automated using linters and automated checkers, together with features like `GitHub Actions`.
- If applicable, test the contribution to ensure it works as intended.
- Thank the contributor for their effort.

The maintainer should make sure that a decision for a contribution is taken in a reasonable time frame (approve, reject, request more changes, etc), so that the repository does not accumulate a large amount of lingering pull requests.

#### Creating a repository

If a new content repository needs to be created from scratch, a good starting point is to clone the [`oer-template`](https://github.com/open-education-hub/oer-template) repository.
This repository contains the basic directory structure for a course, including some tools and other files that should typically be present, on top of which any kind of content can be added.
