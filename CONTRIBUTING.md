# Contributing

These are the defaults for MarcDownHQ projects. When a project has its own `CONTRIBUTING.md`,
`CLAUDE.md`, `AGENTS.md` or `brain/`, those come first: read them before you start.

## Making a change

1. Open an issue first for anything bigger than a small fix, so nobody builds something that will
   not be merged.
2. Work on a branch, never directly on the default branch. Our default branches are not technically
   protected, so this one relies on all of us.
3. Keep a pull request to one topic. Split unrelated changes into separate pull requests.
4. Make sure CI is green and update the docs your change makes wrong.
5. Have someone else look at the pull request when the change is not trivial.

## Commits

A branch should read as a series of steps a reviewer can follow one at a time. Each commit does one
kind of work and leaves the project building and its tests passing: mechanical changes such as moves
and renames first, then behaviour, then tests and docs. Follow the commit message style already used
in the project's history.

## Reporting a security problem

Please do not open a public issue. Follow the [security policy](SECURITY.md).
