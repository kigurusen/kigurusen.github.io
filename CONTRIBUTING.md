# How to Contribute

Thanks for your interest in contributing to this project, it means a lot to me!
This is my personal homepage and project hub, so I'd like to at least try to do everything myself.
Contributions are mostly limited to suggestions and bug reports.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Reporting Bugs and Suggestions](#reporting-bugs-or-suggestions)
- [About Content Changes](#about-content-changes)
- [Improving the Source Code](#improving-the-source-code)

## Code of Conduct

By participating, you are expected to uphold the [code of conduct][coc].
Please report unacceptable behaviour directly to me via a method linked on [my website][website].

## Reporting Bugs or Suggestions

> ### Security Notice
>
> Never report security related issues in public spaces.
> Instead please message me directly and privately using [one of my links][website].

1. Make sure your bug is really a bug and not an error on your side
2. Check if a related [open issue][issues] exists already
3. If not, simply [create a new one](https://github.com/kigurusen/kigurusen.github.io/issues/new)
   - Provide as much context as you can
   - Describe how to reproduce the issue, if possible using a minimal example
   - Keep the issue short and concise while providing as much detail as possible

## About Content Changes

Because this is my personal homepage, pull requests containing content changes will not be merged.
If you want to improve or change the website content, here's what you can do:

- [Submit a suggestion](#reporting-bugs-or-suggestions) detailing why your change is better than the current state
- Message me using [one of my links][website] to discuss your suggestion in detail

## Improving the Source Code

### Before You Start

1. Check if a related [open issue][issues] exists already
2. Message me using [one of my links](website) to discuss the change and how to continue

### Working with Source Code

1. [Fork][fork] the repository
2. To keep your fork updated, add the current project as an upstream remote

   ```sh
   # Add upstream remote
   git remote add upstream git@github.com:kigurusen/kigurusen.github.io.git

   # Update your fork
   git fetch upstream
   ```

3. create a new branch with `git switch -c <new-branch-name> origin/dev`
4. Implement your changes and make sure not to change the website content.
5. Test your changes on different browsers and devices
   - Browsers: at least Chrome and Firefox
   - Operating system: Windows, Android, and ideally Linux
   - Sizes: multiple samples from 360x640 to 2560x1440 in both landscape and portrait mode
   - If accessible: Safari on MacOS and iOS
6. Format the code using [Prettier](https://prettier.io/)
   - Enabling Format on Save is recommended

### Creating a Pull Request

1. Synchronize your fork with upstream
   ```sh
   git fetch upstream HEAD
   git rebase FETCH_HEAD
   ```
2. Fix any merge conflicts and test your changes thoroughly
3. [Open a pull request](https://github.com/kigurusen/kigurusen.github.io/compare) with a clear title and description

[coc]: /CODE_OF_CONDUCT.md
[issues]: https://github.com/kigurusen/kigurusen.github.io/issues
[fork]: https://github.com/kigurusen/kigurusen.github.io/fork
[website]: https://kigurusen.github.io
