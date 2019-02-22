# GitHub Link Formatter for Discourse

This is a Discourse plugin that will convert links to GitHub into the short format that developers are familiar with on GitHub itself.

For example, if a user types:
> This was reported in https://github.com/user/repo/issues/1234.

it will display as:
> This was reported in [user/repo#1234](https://github.com/user/repo/pull/1234).

This works for the following kinds of links, with what their short format looks like on the right.

- **Repositories:** `user/repo`
- **Issues:** `user/repo#1234`
- **Pull Requests:** `user/repo#1234`
- **Commits:** `user/repo@8af46d3`
