## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

This guide provides information on filing issues and guidelines for open source contributors. **Please leave comments / suggestions if you find something is missing or incorrect.**

Contributors are encouraged to collaborate using the following resources in addition to the GitHub [issue tracker](https://github.com/HewlettPackard/<insert repo url here>):

* [Public community meetings][community-meetings]
* Chat with us on the [Insert organization name here] Slack ([get an invitation here](org-slack] ) [external Slack only]
  * [#user-slack-channel][users-slack] for end-user discussions
  * [#dev-slack-channel][dev-slack] for development discussions
* Want long-form communication instead of Slack? We have two distributions lists:
  * [insert-project-name-here-users][users-dl] for end-user discussions
  * [insert-project-name-here-dev][dev-dl] for development discussion
  * [more lists to add]

[NOTE: Add details on how to join the mailing lists]

## Issues

PLEASE READ: If the issue is a security vulnerability, please follow the guidelines in our [security section](SECURITY.md).

If you have suggestions for how this project could be improved, or want to report a bug, open an issue! We'd love all and any contributions. If you have questions, too, we'd love to hear them.

It is a great way to contribute to [insert project name here] by reporting an issue. Well-written and complete bug reports are always welcome! Please open an issue on GitHub and follow the template to fill in required information.

Before opening any issue, please look up the existing [issues](https://insert/url/here) to avoid submitting a duplication.
If you find a match, you can "subscribe" to it to get notified on updates. If you have additional helpful information about the issue, please leave a comment.

When reporting issues, always include:

* [insert detail here]
* [insert detail here]
* [insert detail here]

Because the issues are open to the public, when submitting the log and configuration files, be sure to remove any sensitive information, e.g. user name, password, IP address, and company name. You can
replace those parts with "REDACTED" or other strings like "****".

Be sure to include the steps to reproduce the problem if applicable. It can help us understand and fix your issue faster.

## Pull Requests

We'd also love PRs. If you're thinking of a large PR, we advise opening up an issue first to talk about it, though! Look at the links below if you're not sure how to open a PR. Please submit a PR broken down into small changes bit by bit. A PR consisting of a lot of features and code changes may be hard to review. It is recommended to submit PRs in an incremental fashion.

Note: If you split your pull request to small changes, please make sure any of the changes goes to [insert branch name] will not break anything. Otherwise, it can not be merged until this feature complete.

### Commit Requirements

As [insert organization name here] has integrated the [DCO (Developer Certificate of Origin)](https://probot.github.io/apps/dco/) check tool, contributors are required to sign off that they adhere to those requirements by adding a `Signed-off-by` line to the commit messages. Git has even provided a `-s` command line option to append that automatically to your commit messages, please use it when you commit your changes.

```bash
$ git commit -s -m 'This is my commit message'
```

Commit your changes if they're ready:

```bash
git add -A
git commit -s #-a
git push --force-with-lease $user my_feature
```

The commit message should follow the convention on [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/). Be sure to include any related GitHub issue references in the commit message. See [GFM syntax](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) for referencing issues and commits.

To help write conformant commit messages, it is recommended to set up the [git-good-commit](https://github.com/tommarshall/git-good-commit) commit hook. Run this command in the [insert component name here] repository's root directory:

```sh
curl https://cdn.rawgit.com/tommarshall/git-good-commit/v0.6.1/hook.sh > .git/hooks/commit-msg && chmod +x .git/hooks/commit-msg
```

### Documentation

Update the documentation if you are creating or changing features. Good documentation is as important as the code itself.

The main location for the documentation is the [website repository](https://github.com/HewlettPackard/doc-repository). The images referred to in documents can be placed in `docs/img` in that repo.

Documents are written with Markdown. See [Writing on GitHub](https://help.github.com/categories/writing-on-github/) for more details.

## Submitting a pull request

1. [Fork][fork] and clone the repository.

1. Configure and install the dependencies: [ insert example here ].

1. Make sure the tests pass on your machine: [ insert example here], note: these tests also apply the linter, so there's no need to lint separately.

1. Create a new branch: `git checkout -b my-branch-name`. Please use appropriate prefixes for the branch name as given below:
   `bugfix/<my-branch-name>` for bugfix branches
   `feature/<my-branch-name>` for feature branches
   `hotfix/<my-branch-name>` for urgent bugfix contributions

   If your contribution does not fit in any of the above categories, then use the `<username>/<my-branch-name>` name format for your branch.

1. Make your change, add tests, and make sure the tests still pass.

1. Push to your fork and [submit a pull request][pr].

1. Pat your self on the back and wait for your pull request to be reviewed and merged.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the [style guide][style]. Any linting errors should be shown when running [ insert example here].
- Write and update tests.
- Keep your changes as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write a [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

Work in Progress pull requests are also welcome to get feedback early on, or if there is something blocked you.

## Developing and proposing new features.

### The following simple process can be used to submit new features or changes to the existing code.

- See if your feature is already being worked on. Check both the [Issues](https://github.com/url/here) and the [PRs](https://github.com/url/here) in the main [insert project name here] repository as well as the [Community repository](https://github.com/insert/url/here).
- If the proposal is simple or small, and an issue for the proposal does not exist, then open an issue using the feature template.
- Otherwise, if it is a significant change then submit(open PR) the new proposal at [community/proposals/new](https://github.com/insert/url/here) using the already existing [template](PROPOSAL_TEMPLATE.md). This will insert the proposal into the queue for discussion and approval.
- The proposal must be labeled as "kind/proposal" - check examples [here](include some example)
- The proposal can be modified and adapted to meet the requirements from the community, other maintainers and contributors. The overall architecture needs to be consistent to avoid duplicate work in the [Roadmap](https://github.com/project/wiki#roadmap).
- Proposal should be discussed at Community meeting [Community Meeting agenda](insert link here) to be presented to maintainers and contributors.
- When reviewed and approved it can be implemented either by the original submitter or anyone else from the community which we highly encourage. Open PRs in the respective repositories with all the necessary code and test changes as described in the current document.
- Once implemented or during the implementation, the PRs are reviewed by maintainers and contributors, following the best practices and methods.
- After merging the new PRs, the proposal must be moved to [community/proposals/complete](insert url here) and marked as done!
- You have made [insert project name here] even better, congratulations. Thank you!

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)

[fork]: /fork
[pr]: /compare
[style]: https://google.github.io/styleguide/shellguide.html
[code-of-conduct]: CODE_OF_CONDUCT.md

[ slack ]: https://hpe.slack.com
[community-meetings]: MEETING_SCHEDULE.md
[users-slack]: https://slack.url/user
[dev-slack]: https://slack.url/dev
[org-slack]: https://slack.url
[users-dl]: user-email@org.com
[dev-dl]: dev-email@org.com

