# - CMS Changelog (CMSchangelog) DRAFT -

Index of pages:
---------------

* [Summary](/README.md#Summary)
* [Introduction](/README.md#Introduction)
* [CMS Changelog (CMSchangelog)](/CHANGELOG.md)
* [Why Explicit Versioning](/WHY.md)
* [FAQ](/FAQ.md)
* [ABOUT](/ABOUT.md)
* [Who is using CMS Versioning?](/USERS.md)

# - CMS Changelog (CMSchangelog) DRAFT -


# <a name="Summary"></a>Summary

A changelog is a file which contains a curated, chronologically ordered list of notable changes for each version of a project.

The point of a change log is to make it easier for users and contributors to see precisely what notable changes have been made between each release (or version) of the project.

Given a update ADDITIONS.ENHANCEMENTS.BUGFIXES.SECURITY.REMOVED.DEPRECATED, track the:

|KEYWORD | DEFINITION
--------|--------
Additions| for new features.
Enhancements| for changes in existing functionality.
Bugfixes| for any bug fixes.
security| to invite users to upgrade in case of vulnerabilities.
removed| for deprecated features removed in this release.
deprecated| for once-stable features removed in upcoming releases.

[Additional words](/CHANGELOG.md)are available as introduction to each change of the list the ADDITIONS, ENHANCEMENTS, BUGFIXES, SECURITY, REMOVED, DEPRECATED.
  
**If you'd like to leave feedback, please [open an issue on GitHub](https://github.com/colomet/CMSchangelog/issues).**
  
# - CMS Changelog (CMSchangelog) DRAFT -  

# <a name="Introduction"></a>Introduction

In the world of software management there exists a dread place called "dependency hell." The bigger your system grows and the more packages you integrate into your software, the more likely you are to find yourself, one day, in this pit of despair.

In systems with many dependencies, releasing new package versions can quickly become a nightmare. ///If the dependency specifications are too tight, you are in danger of version lock (the inability to upgrade a package without having to release new versions of every dependent package). If dependencies are specified too loosely, you will inevitably be bitten by version promiscuity (assuming compatibility with more future versions than is reasonable).///
Dependency hell is where you are when version lock and/or version promiscuity prevent you from easily and safely moving your project forward.
///
**In CMS (WordPress, Joomla, Drupal) also exist the problem of the complements (Modules, Aplications, Plugins, Components, add-ons ...) where we need to take care of the code once we integrate our development in the CMS.** We need to know what it change in order to know if it will affect our own development.

Another problem we find is about keepachangelog, keepachangelog is too self code focus and some times the developers need more information.

As a solution to this problem, I propose a simple set of rules and requirements that dictate how version numbers are assigned and incremented in a base of 4 digit instead of the 3 digits of [Semantic Versioning](http://semver.org/), in that way we split in a different digit each one of the situations.

These rules are based on but not necessarily limited to pre-existing widespread common practices in use in both closed and open-source software.


I call this system ["CMS Changelog (CMSchangelog)"](/CHANGELOG.md) Under this scheme, change logs and the way they change convey meaning about the underlying code and what has been modified from one version to the next.


   <a href="https://twitter.com/share" class="twitter-share-button" data-show-count="false">Tweet</a><script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
   
   <script src="https://apis.google.com/js/platform.js" async defer></script>
   <g:plus action="share"></g:plus>
 
---



[Start page](./)
