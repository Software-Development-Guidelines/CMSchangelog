# @since (Changelogs)

Every function, hook, class, and method should have a corresponding `@since` version associated with it (more on that below).

No HTML should be used in the descriptions for `@since` tags, though limited Markdown can be used as necessary, such as for adding backticks around variables, arguments, or parameter names, e.g. `$variable`

Versions should be expressed in the 3-digit `x.x.x` style:


1 `* @since 4.4.0`

If significant changes have been made to a function, hook, class, or method, additional `@since` tags, versions, and descriptions should be added to provide a changelog for that function.

“Significant changes” include but are not limited to:

* Adding new arguments or parameters
* Required arguments becoming optional
* Changing default/expected behaviors
* Functions or methods becoming wrappers for new APIs

PHPDoc supports multiple `@since` versions in DocBlocks for this explicit reason. When adding changelog entries to the `@since` block, a version should be cited, and a description should be added in sentence case and form and end with a period:

1 ` * @since 3.0.0`

2 ` * @since 3.8.0 Added the 'post__in' argument.`

3 ` * @since 4.1.0 The '$force' parameter is now optional.`


### Reference 
[codex](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/php/#since-section-changelogs)
