# MAML for Zed

Syntax highlighting, bracket matching, indentation and an outline of keys for
[MAML](https://maml.dev) files in Zed. The parser is
[tree-sitter-maml](https://github.com/0x80/tree-sitter-maml).

## Install locally

Run **zed: install dev extension** from the command palette and pick this directory.

`rev` in `extension.toml` pins a grammar commit. After the grammar changes, set `rev`
to the new commit and reinstall. To test an unpushed grammar change, point
`repository` at the local checkout with a `file://` URL.
