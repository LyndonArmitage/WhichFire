# WhichFire Gemini Search Engine

This repository contains the code and other related documents for creating the
Gemini Search Engine **WhichFire**.

## Conventions

This project uses the following conventions:

### Semantic Versioning

[Semantic Versioning](https://semver.org/spec/v2.0.0.html) describes a sensible
way of doing versioning using a `MAJOR.MINOR.PATCH` convention.

### Keep a Changelog

[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) presents a standard
way of keeping a changelog for changes done to the project. These changes are
kept in `CHANGELOG.md` in Markdown format.

### Short Lines

This is a loose convention meant to ensure readability on most devices.

Most lines in code and text files should limit themselves to 80 to 100 columns.
Generally, the closer to 80 the better.

Obviously, this is sometimes hard to achieve. So use your common sense to avoid
lines that stretch on for seemingly forever.

### Git

[Git](https://git-scm.com/) is being used as the source control management
system for this project.

#### Commits

This project **does not** use Conventional Commits as a standard for its commit
messages. Instead, it relies on the committer adhering to the guidelines
presented in [git-scm](https://git-scm.com/docs/git-commit#_discussion) and
here, summarized as the following:

* First line should be treated as a title
* First line should be no longer than 50 characters
* First line should be written in the present tense, in an imperative way e.g.
  "fixes issue with cats and dogs" or "adds cool hat"
* There should be a blank line between the first line and other lines
* Other lines (the body of the commit) can be written in other tenses and a
  non-imperative way, but generally should explain the commit with enough
  context
* If referencing an issue in an issue tracker, try to include it in first line
  and link to it in the body of the commit
* Body lines should wrap at 72 characters, so they fit nicely in terminal git
  tools.

Essentially, you should be able to read the commit history as a summary of what
changes were done. So messages like "WIP" should be avoided.

#### Branches

Branches should encapsulate a singular feature or concept.

If you're merging a branch into `master` you can opt to squash your commits,
but the above commit conventions still apply to the squashed commit message.
