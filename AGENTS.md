# Agent notes

## Running tests

    uvx --with django --with-editable . python tests/manage.py test testapp

`tox` runs the full matrix. The pre-commit hooks (ruff, ruff format, biome
for the JavaScript, etc.) run on commit.

## Commits

Commit feature by feature. Keep commit messages minimal and don't repeat
what's visible in the diff itself.

Don't add attribution (no `Co-Authored-By` lines or "Generated with" footers)
to commit messages or pull request descriptions.

## Changelog

Keep `CHANGELOG.rst` up to date: add user-visible changes to the "Next
version" section in the same commit as the change.
