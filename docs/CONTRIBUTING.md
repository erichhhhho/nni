# Contributing to Neural Network Intelligence (NNI)

Great!! We are always on the lookout for more contributors to our code base.

Firstly, if you are unsure or afraid of anything, just ask or submit the issue or pull request anyways. You won't be yelled at for giving your best effort. The worst that can happen is that you'll be politely asked to change something. We appreciate any sort of contributions and don't want a wall of rules to get in the way of that.

However, for those individuals who want a bit more guidance on the best way to contribute to the project, read on. This document will cover all the points we're looking for in your contributions, raising your chances of quickly merging or addressing your contributions.

Looking for a quickstart, get acquainted with our [Get Started](./docs/GetStarted.md) guide.

There are a few simple guidelines that you need to follow before providing your hacks. 

## Raising Issues

When raising issues, please specify the following:
- Setup details needs to be filled as specified in the issue template clearly for the reviewer to check.
- A scenario where the issue occurred (with details on how to reproduce it).
- Errors and log messages that are displayed by the software.
- Any other details that might be useful.

## Submit Proposals for New Features

- There is always something more that is required, to make it easier to suit your use-cases. Feel free to join the discussion on new features or raise a PR with your proposed change. 

- Fork the repository under your own github handle. After cloning the repository. Add, commit, push and sqaush (if necessary) the changes with detailed commit messages to your fork. From where you can proceed to making a pull request. 

## Contributing to Source Code and Bug Fixes

Provide PRs with appropriate tags for bug fixes or enhancements to the source code. Do follow the correct naming conventions and code styles when you work on and do try to implement all code reviews along the way.

If you are looking for How to go about contributing and debugging the NNI source code, you can refer our [How to Contribute](./docs/HowToContribute.md) file in the `docs` folder.

Similarly for [writing trials](./docs/WriteYourTrial.md) or [starting experiments](StartExperiment.md). For everything else, refer [here](https://github.com/Microsoft/nni/tree/master/docs).

## Solve Existing Issues
Head over to [issues](https://github.com/Microsoft/nni/issues) to find issues where help is needed from contributors. You can find issues tagged with 'good-first-issue' or 'help-wanted' to contribute in. 

A person looking to contribute can take up an issue by claiming it as a comment/assign their Github ID to it. In case there is no PR or update in progress for a week on the said issue, then the issue reopens for anyone to take up again. We need to consider high priority issues/regressions where response time must be a day or so. 

## Code Styles & Naming Conventions  
We follow [PEP8](https://www.python.org/dev/peps/pep-0008/) for Python code and naming conventions, do try to adhere to the same when making a pull request or making a change. One can also take the help of linters such as `flake8` or `pylint`
