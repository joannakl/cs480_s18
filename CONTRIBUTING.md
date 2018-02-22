# Contributing to this website

### What to contribute

* __Content__ Generally, content is determined by Professor Joanna Klukowska, so content contributions are discouraged.  However, if you feel that some useful information is missing from the site, by all means submit an issue.
* __Formatting and Grammar__ If you notice any flaws in the site, please submit an issue.
* __Bug Fixes__ If you find any issues with the code, please submit an issue.
* __Fixes to Existing Issues__ Always welcome :) See guide below for instructions on getting your fix approved.

## How to contribute

### Issues

All contributions to this site start life as issues.  If you find a fault in the site, please submit it through Github's built-in [issue tracker](https://github.com/joannakl/cs480_s18/issues).  

Each issue starts a conversation among the team.  You are encouraged to join in on any issue's discussion by confirming / replicating the bug on your browser, discovering the scope of the bug, triaging its probable cause, or suggesting possible fixes.

### Issue Assignment

If you'd like to be the one to solve an issue, comment on its discussion page asking to claim it.  If Prof. Klukowska would like you to work on it, she will assign it to you and give you the go-ahead.  Once you have that, you're free to start working.

### Fixing the Issue

The first step to making your solution is to create your own fork of the repository through Github.  Once you have that, clone it to your computer and work on it locally.

To check your work as you develop your fix, you may find the following tools helpful:

* [__Jekyll__](https://jekyllrb.com/): This can be used to build the site locally so you can see the changes you've made.  Once you have Jekyll installed, run `jekyll build` in the project's root to build .html's to ./\_site.  These can then be viewed in your browser.

* [__grip__](https://github.com/joeyespo/grip): If you're contributing to a Markdown file, like this one or README, grip allows you to render it using Github's styling.

### Submitting a Fix

Once you have the fix to your issue completed, push it to your forked repository.  `git pull` against the main repo to integrate changes made while you were fixing your issue.  Ensure there are no merge conflicts.  

Once that's done, make a [pull request](https://github.com/joannakl/cs480_s18/pulls).  In the message, describe the changes you've made.  Reference the issue page in your message.  Other contributors will review your fix and ensure it's correct.  Once that's happened, Prof. Klukowska will merge your fix into the main repo.  


