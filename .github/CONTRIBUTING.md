# Contributing to osprey-ptbr

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to osprey-ptbr (hugo osprey template translated to pt-BR), which are hosted in the [osprey-ptbr](https://github.com/ddspog/osprey-ptbr) on GitHub. These are just guidelines, not rules, use your best judgment and feel free to propose changes to this document in a pull request.

## Table Of Contents

[What should I know before I get started?](#what-should-i-know-before-i-get-started)

* [Code of Conduct](#code-of-conduct)
* [osprey-ptbr](#osprey-ptbr)

[How Can I Contribute?](#how-can-i-contribute)

* [Reporting Bugs](#reporting-bugs)
* [Suggesting Enhancements](#suggesting-enhancements)
* [Your First Code Contribution](#your-first-code-contribution)
* [Pull Requests](#pull-requests)

[Styleguides](#styleguides)

* [Git Commit Messages](#git-commit-messages)
* [Tests Styleguide](#tests-styleguide)

[Additional Notes](#additional-notes)

* [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## What should I know before I get started

### Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [ddspog@gmail.com](mailto:ddspog@gmail.com).

### osprey-ptbr

osprey-ptbr it's a [Hugo](hhttps://gohugo.io/) [osprey](https://github.com/tomanistor/osprey) forked theme translated to pt-BR. It follows the same art style as the original, crediting the author.

The main purpose of these project it's to make translation of this theme faster. Many projects can be made using this, using portuguese language. And maybe, this forked theme can evolve to multi-language support.

Further details on how to use this package are available on the [Wiki](https://github.com/ddspog/osprey-ptbr/wiki).

## How Can I Contribute

### Reporting Bugs

This section guides you through submitting a bug report for osprey-ptbr. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Please use the issues templates, for better reading and understanding of the rest of team.

#### Before Submitting A Bug Report

* **Check it carefully.** You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem [in the latest version of osprey-ptbr](https://github.com/ddspog/osprey-ptbr).
* **Check the FAQs on the forum** for a list of common questions and problems.
* **Perform a [cursory search](https://github.com/ddspog/osprey-ptbr/issues?utf8=%E2%9C%93&q=is%3Aissue+user%3Addspog+)** to see if the problem has already been reported. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on [osprey-ptbr](https://github.com/ddspog/osprey-ptbr/issues/new) and provide the following information.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started this seed, e.g. which command exactly you used in the terminal, or how you compiled this seed otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an command, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. You can use [this tool](https://getsharex.com/) to record GIFs on OSX and Windows,
 and [this tool](http://www.cockos.com/licecap/) on OSX or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If you're reporting that the seed crashed**, include a crash report with a stack trace from Browser used, or other tool. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
* **If the problem is related to performance**, include a [CPU profile capture and a screenshot](http://flight-manual.atom.io/hacking-atom/sections/debugging/#diagnose-performance-problems-with-the-dev-tools-cpu-profiler) with your report.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of osprey-ptbr) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of osprey-ptbr?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of osprey-ptbr are you using**?
* **What's the name and version of the OS you're using**?
* **Are you running osprey-ptbr in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
* **Which keyboard layout are you using?** Are you using a US layout or some other layout?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for osprey-ptbr, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please
 [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). If you'd like, you can use [this template](#template-for-submitting-enhancement-suggestions) to structure the information.

#### Before Submitting An Enhancement Suggestion

* **Check if this enhancement it's already available**. Most importantly, check if you can get the desired behavior by changing configuration.
* **Perform a [cursory search](https://github.com/ddspog/osprey-ptbr/issues?utf8=%E2%9C%93&q=is%3Aissue+user%3Addspog+)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Explain why this enhancement would be useful**.
* **Specify the name and version of the OS you're using.**

##### Template For Submitting Bug Reports or Enhancements

You can find the issues templates [here](ISSUE_TEMPLATE.md). But they're already will be loaded on any new issue you open. The template also has some tips to write the issue as enhancement suggestion.

### Your First Code Contribution

Unsure where to begin contributing to osprey-ptbr? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues](https://github.com/ddspog/osprey-ptbr/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Abeginner+label%3Ahelp-wanted+user%3Aatom+sort%3Acomments-desc+) - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues](https://github.com/ddspog/osprey-ptbr/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Ahelp-wanted+sort%3Acomments-desc+) - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

* Include screenshots and animated GIFs in your pull request whenever possible.
* Include thoughtfully-worded, well-structured tests for components on folders at each component. Run them using `go test -v`. Create new tests based on [Tests Styleguide](#tests-styleguide)
* End files with a newline.
* Place imports in the following order:
  * Utility Go Packages (such as `net/http`)
  * Core Packages (such as `github.com/gin-gonic/gin`)
  * Local Packages (using github paths)
* Avoid platform-dependent code.
* Using a plain `return` when returning explicitly at the end of a function.
  * Not `return null`, `return undefined`, `null`, or `undefined`

## Styleguides

### Git Commit Messages

* Use commitzen style
* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 50 characters or less
  * And the rest with 72 characters or less
* End all commits summaries Referencing issues or pull requests.
  * eg: Ref #12
* Considering starting with abbreviations as:
  * Add: for new functionality
  * Mod: algorithm or location
  * Ref: new stuff for class
  * Fix: #42 issue
  * Rem: class deprecated
  * Rea: removing comments on local
* Consider starting the commit message with an applicable emoji:
  * :art: `:art:` when improving the format/structure of the code
  * :racehorse: `:racehorse:` when improving performance
  * :non-potable_water: `:non-potable_water:` when fixing DB
  * :memo: `:memo:` when writing docs
  * :penguin: `:penguin:` when fixing something on Linux
  * :apple: `:apple:` when fixing something on Mac OS
  * :checkered_flag: `:checkered_flag:` when fixing something on Windows
  * :bug: `:bug:` when fixing a bug
  * :fire: `:fire:` when removing code or files
  * :white_check_mark: `:white_check_mark:` when adding tests
  * :green_heart: `:green_heart:` when fixing CI
  * :lock: `:lock:` when dealing with security
  * :arrow_up: `:arrow_up:` when upgrading dependencies
  * :arrow_down: `:arrow_down:` when downgrading dependencies
  * :shirt: `:shirt:` when removing warnings
  * :lipstick: `:lipstick:` when improving UI
  * :construction: `:construction:` for WIP (work-in-progress)
  * :speaker: `:speaker:` when adding logging
  * :mute: `:mute:` when reducing logging
  * :bulb: `:bulb:` for new idea
  * :snowflake: `:snowflake:` when changing configuration
  * :rocket: `:rocket:` deployment related

### Git commit template

Use this wherever you can put commit templates.

```git
################################################T#####################M
# Capitalized, short (50 chars or less) summary                       #
#                                                                     #
# Details.  Wrap it to about 72 characters or so. Write your commit   #
# message in the imperative: "Fix bug" and not "Fixed bug"            #
#                                                                     #
# Ref #45                  always end with this                       #
#######################################################################
Title :construction:

Summary

Ref
#######################################################################
# Considering starting with abbreviations as:                         #
# Add: new functionality   | Mod: algorithm or location               #
# Ref: new stuff for class | Fix: #42 issue                           #
# Rem: class deprecated    | Rea: removing comments on local          #
#######################################################################
# Consider ending the commit message with an applicable emoji:        #
# :art: improving code format | :racehorse: improving performance     #
# :memo: when writing docs    | :non-potable_water: DB related        #
# :penguin: fixing on Linux   | :apple: fixing on Mac OS              #
# :checkered_flag: on Windows | :bug: when fixing a bug               #
# :fire: removing code        | :white_check_mark: when adding tests  #
# :lock: security             | :arrow_up: upgrading dependencies     #
# :shirt: removing warnings   | :arrow_down: downgrading dependencies #
# :green_heart: fixing CI     | :lipstick: improving UI               #
# :bulb: new idea             | :construction: work in progress       #
# :mute: reducing logging     | :speaker: adding loggin               #
# :rocket: deployment related | :snowflake: changing configuration    #
#######################################################################
```

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. We  encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

Please open an issue on if you have suggestions for new labels, and if you notice some labels are missing on some repositories, then please open an issue on that repository.

#### State of work

We use Github Project boards to show current state of work on issues, enhancements or user stories.