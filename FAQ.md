Index of pages:
---------------

* [Summary](/README.md)
* [Introduction](/README.md)
* [Explicit Changelog](/CHANGELOG.md)
* [Why Explicit Changelog](/WHY.md)
* [FAQ](/FAQ.md)
* [ABOUT](/ABOUT.md)
* [Who is using Explicit Changelog?](/USERS.md)


# FAQ

## How can I minimize the effort required?
Always have an "Unreleased" section at the top for keeping track of any changes.

This serves two purposes:

* People can see what changes they might expect in upcoming releases
* At release time, you just have to change "Unreleased" to the version number and add a new "Unreleased" header at the top.

## Which type of changelog should avoid?
Alright…let’s get into it.

* Dumping a diff of commit logs. Just don’t do that, you’re helping nobody.
* Not emphasizing deprecations. When people upgrade from one version to another, it should be painfully clear when something will break.
* Dates in region-specific formats. In the U.S., people put the month first ("06-02-2012" for June 2nd, 2012, which makes no sense), while many people in the rest of the world write a robotic-looking "2 June 2012", yet pronounce it differently. 

## Is there a standard change log format?
Sadly, no. Calm down. I know you're furiously rushing to find that link to the GNU change log style guide, or the two-paragraph GNU NEWS file "guideline". The GNU style guide is a nice start but it is sadly naive. There's nothing wrong with being naive but when people need guidance it's rarely very helpful. Especially when there are many situations and edge cases to deal with.

## What should the change log file be named?
Well, if you can’t tell from the example above, CHANGELOG.md is the best convention so far.

Some projects also use HISTORY.txt, HISTORY.md, History.md, NEWS.txt, NEWS.md, News.txt, RELEASES.txt, RELEASE.md, releases.md, etc.

It’s a mess. All these names only makes it harder for people to find it.

## Why can’t people just use a git log diff?
Because log diffs are full of noise — by nature. They could not make a suitable change log even in a hypothetical project run by perfect humans who never make typos, never forget to commit new files, never miss any part of a refactoring. The purpose of a commit is to document one atomic step in the process by which the code evolves from one state to another. The purpose of a change log is to document the noteworthy differences between these states.

As is the difference between good comments and the code itself, so is the difference between a change log and the commit log: one describes the why, the other the how.

## Can change logs be automatically parsed?
It’s difficult, because people follow wildly different formats and file names.

Vandamme is a Ruby gem created by the Gemnasium team and which parses many (but not all) open source project change logs.

## Why do you alternate between spelling it "CHANGELOG" and "change log"?
"CHANGELOG" is the name of the file itself. It's a bit shouty but it's a historical convention followed by many open source projects. Other examples of similar files include README, LICENSE, and CONTRIBUTING.

The uppercase naming (which in old operating systems made these files stick to the top) is used to draw attention to them. Since they're important metadata about the project, they could be useful to anyone intending to use or contribute to it, much like [open source badges project](http://shields.io/).

When I refer to a "change log", I'm talking about the function of this file: to log changes.

## What about yanked releases?

Yanked releases are versions that had to be pulled because of a serious bug or security issue. Often these versions don't even appear in change logs. They should. This is how you should display them:

		## 0.0.5 - 2014-12-13 [YANKED]

The <[YANKED]> tag is loud for a reason. It's important for people to notice it. Since it's surrounded by brackets it's also easier to parse programmatically.
Should you ever rewrite a change log?

Sure. There are always good reasons to improve a change log. I regularly open pull requests to add missing releases to open source projects with unmaintained change logs.

It's also possible you may discover that you forgot to address a breaking change in the notes for a version. It's obviously important for you to update your change log in this case.


---



[Start page](./)

