# MAML for Zed

Syntax highlighting, bracket matching, indentation and outline for
[MAML](https://maml.dev) files in Zed, built on
[tree-sitter-maml](../tree-sitter-maml).

## Install locally

Run **zed: install dev extension** from the command palette and pick this directory.

`extension.toml` points at the grammar through a `file://` URL and a commit SHA. After
committing a grammar change, update `rev` and reinstall the extension. Before publishing
to `zed-industries/extensions`, replace the `file://` URL with the grammar's public
repository.
