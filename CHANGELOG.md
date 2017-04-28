Index of pages:
---------------

* [Summary](/README.md)
* [Introduction](/README.md)
* [CMS Changelog (CMSchangelog)](/CHANGELOG.md)
* [Why Explicit Versioning](/WHY.md)
* [FAQ](/FAQ.md)
* [ABOUT](/ABOUT.md)
* [Who is using CMS Versioning?](/USERS.md)


# CMS Changelog (CMSchangelog)

A good change log sticks to these principles:
--

 * It’s made for humans, not machines, so legibility is crucial.
 * Write all dates in YYYY-MM-DD format. It’s international, sensible, and language-independent.
 * Each version should:
   * List its release date in the above format.
   * Group changes to describe their impact on the project, as follows:
     * **ADDITIONS** for new features.
     * **ENHANCEMENTS** for changes in existing functionality.
     * **FBUGIXED** for any bug fixes.
     * **SECURITY** to invite users to upgrade in case of vulnerabilities.
     * **REMOVED** for deprecated features removed in this release.
     * **DEPRECATED** for once-stable features removed in upcoming releases.
 * Always have an "UNRELEASED" section at the top for keeping track of any changes. This serves two purposes:
   *  People can see what changes they might expect in upcoming releases
   *  At release time, you just have to change "Unreleased" to the version number and add a new "Unreleased" header at the top.
 * List of Files Revised
   * Added
   * Modified
   * Copied or renamed 
 

For a more detailed information you can use FEATURE, ENHANCED, FIXED, SECURITY, REMOVED, DEPRECATED. inside the next changelog keywords:
 
Adds, Contains, Improves, Fixes, Fixes an issue,  Fixes a compatibility issue, Introduces, Introduces a feature, Introduces the, Made it possible, Makes,  Only includes, Prevent, Prevented, Removes, Removes unused, Rename, Setup, Specify, Splits, Throws, Updated.
 
  
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](http://tools.ietf.org/html/rfc2119).
  

1. Software using CMS Changelog MUST declare all the changes of the software. This changes
could be declared in the code itself or exist strictly in documentation.
However it is done, it should be precise and comprehensive.

1. The Format MUST NOT be change
Changelog files are organized by paragraphs, which define a unique change within a function or file  

1. Contributors name SHOULD be writen in the Changelog and the commit MAY be added too
When you introduce someone else’s changes, put the contributor’s name in the ending of the paragraph of the change of the changelog   rather than in other place.
props to @UserName;
props to @UserName for the suggestion;
props to @UserName for the report;
If there is an Git or CVS commit, MUST be afther the name of the contributor. In other words, write this: 
props to @UserName; see #670
  
1. CMSchangelog MAY use CMSver
SEMVER or other ways to name your releases are allowed but we RECOMMENDED to use CMSver as we believe it could adapt better to each situation.

Explicitly mention whether the project follows [CMS Versioning](https://software-development-guidelines.github.io/CMScver/).


1. Each versions MUST Include Dates with format ISO 8601
Include release date for each release you do. People like to know when a release was done. The ISO 8601 format YYYY-MM-DD works logically from largest to smallest, doesn't overlap in ambiguous ways with other date formats, and is an [ISO standard](http://www.iso.org/iso/home/standards/iso8601.htm). Thus, it is the recommended date format for change logs.
(Example: 2015-10-21 for October 21, 2015.)

1. One sub-section per version
Easy to link to any section (hence Markdown over plain text).

1. List releases in reverse-chronological order
Newest on top.

1. Always inform about the "BREAKING CHANGES" 
for keeping track of any changes.



---



[Start page](./)

