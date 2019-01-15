# Overview

[![Join the chat at https://gitter.im/nektos/act](https://badges.gitter.im/nektos/act.svg)](https://gitter.im/nektos/act?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Run your [GitHub Actions](https://developer.github.com/actions/) locally!  Why would you want to do this?  Two reasons:

* **Fast Feedback** - Rather than having to commit/push every time you want test out the changes you are making to your `main.workflow` file (or for any changes to embedded GitHub actions), you can use `act` to run the actions locally.  The [environment variables](https://developer.github.com/actions/creating-github-actions/accessing-the-runtime-environment/#environment-variables) and [filesystem](https://developer.github.com/actions/creating-github-actions/accessing-the-runtime-environment/#filesystem) are all configured to match what GitHub provides.
* **Local Task Runner** - I love [make](https://en.wikipedia.org/wiki/Make_(software)).  However, I also hate repeating myself.  With `act`, you can use the GitHub Actions defined in your `main.workflow` file to replace your `Makefile`!  