# Contributing

We love contributions! and we'd love to have you hang out in our community.

**Impostor syndrome disclaimer**: We want your help. No, really.

There may be a little voice inside your head that is telling you that you're not
ready to be an open source contributor; that your skills aren't nearly good
enough to contribute. What could you possibly offer a project like this one?

We assure you - the little voice in your head is wrong. If you can write code at
all, you can contribute code to open source. Contributing to open source
projects is a fantastic way to advance one's coding skills. Writing perfect code
isn't the measure of a good developer (that would disqualify all of us!); it's
trying to create something, making mistakes, and learning from those
mistakes. That's how we all improve, and we are happy to help others learn.

Being an open source contributor doesn't just mean writing code, either. You can
help out by writing documentation, tests, or even giving feedback about the
project (and yes - that includes giving feedback about the contribution
process). Some of these contributions may be the most valuable to the project as
a whole, because you're coming to the project with fresh eyes, so you can see
the errors and assumptions that seasoned contributors have glossed over.

## What Can I Do?

* Tackle any [issues](https://github.com/ELSPL/ml-community/issues) you wish! 
  Also have a look at if the issue is already assigned to someone - this helps us make sure
  that work is not duplicated if the issue is already being worked on by members. If its assigned it will have label "Status: In Progress"
* Contribute code you already have. It does not need to be perfect! We will help you clean
  things up, test it, etc.
* Make a tutorial or example of how to do something.
* Improve documentation of a feature you found troublesome. You can add tutorials, books or any helpful resources you found necessary while working in this community. 
* File a new issue if you run into problems!

## Ground Rules

The goal is to maintain a diverse community that's pleasant for everyone. Please
be considerate and respectful of others by following our 
[code of conduct](https://github.com/ELSPL/ml-community/blob/master/CODE_OF_CONDUCT.md). 

Other items:

* Each pull request should consist of a logical collection of changes. You can
  include multiple bug fixes in a single pull request, but they should be related.
  For unrelated changes, please submit multiple pull requests.
* Do not commit changes to files that are irrelevant to your feature or bugfix
  (eg: .gitignore).
* Be willing to accept criticism and work on improving your code; we don't want
  to break other users' code, so care must be taken not to introduce bugs.
* Be aware that the pull request review process is not immediate, and is
  generally proportional to the size of the pull request.

## Reporting issues

The easiest way to get involved is to report issues you encounter when using our repository or by
requesting something you think is missing.

* Head over to the [issues](https://github.com/ELSPL/ml-community/issues) page.
* Search to see if your issue already exists or has even been solved previously.
* If you indeed have a new issue or request, click the "New Issue" button. Select type of Issue.
* Fill in as much of the issue template as is relevant. Please be as specific as possible. 
  Include the version of the code you were using, as well as what operating system you 
  are running. If possible, include complete, minimal example code that reproduces the problem.
* Whenever possible, please also include a [short, self-contained code example](http://sscce.org) that demonstrates the problem.

## Contributing code

First of all, thanks for your interest in contributing!

- If you are new to git/Github, please take check a few tutorials
  on [git](https://git-scm.com/docs/gittutorial) and [GitHub](https://guides.github.com/).
- The basic workflow for contributing is:
  1. [Fork](https://help.github.com/articles/fork-a-repo/) the repository
  2. [Clone](https://help.github.com/articles/cloning-a-repository/) the repository to create a local copy on your computer:
    ```
    git clone git@github.com:${user}/ml-community.git
    cd ml-community
    ```
  3. Create a branch for your changes
    ```
    git checkout -b name-of-your-branch
    ```
  4. Make change to your local copy of the ml-community repository
  5. Commit those changes
    ```
    git add file1 file2 file3
    git commit -m 'a descriptive commit message'
    ```
  6. Push your updated branch to your fork
    ```
    git push origin name-of-your-branch
    ```
  7. [Open a pull request](https://help.github.com/articles/creating-a-pull-request/) to the ELSPL/ml-community

### Merging
Once we're all happy with the pull request, it's time for it to get merged in. Only the
maintainers can merge pull requests and you should never merge a pull request you have commits
on as it circumvents the code review. If this is your first or second pull request, we'll
likely help by rebasing and cleaning up the commit history for you. As your developement skills
increase, we'll help you learn how to do this.
