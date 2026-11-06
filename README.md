# Linux & Systems Administration References

A collection of lightweight, browser-based references for Linux and systems-administration workflows.

## Included tools

### Vim Cheat Sheet

A structured Vim reference covering navigation, editing, visual mode, registers, buffers, windows, search, replacement, macros, and clipboard-related commands.

[Open the Vim Cheat Sheet](./vim-cheatsheet.html)

### Sudoers Rule Explorer

An interactive reference for exploring sudoers rule structure and understanding how users, hosts, run-as identities, commands, and tags fit together.

[Open the Sudoers Rule Explorer](./sudoers_rule_explorer.html)

## Run locally

No build process or package installation is required.

Clone or download the repository, then open either HTML file in a modern browser. The pages are static client-side tools and do not require an application backend.

The Vim page loads two illustrative images from the official Vim website. An internet connection is required for those images; the rest of the reference is local.

## Accuracy and safe use

These are learning references, not substitutes for authoritative documentation.

- Verify Vim behavior against the installed version and `vim(1)` / `:help`.
- Review sudoers syntax and policy using `man sudoers` on the target system.
- Validate sudoers changes with `visudo` and understand the impact before applying them.
- Never copy example sudo rules into production without reviewing the security implications.

## Project scope

The repository currently contains static reference pages. It does not modify system configuration, execute shell commands, or inspect the host operating system.

## License

The original project code and authored reference material are licensed under the MIT License. See [LICENSE](./LICENSE).

The Vim name and externally loaded Vim images belong to their respective rights holders. Their inclusion is for identification and reference and does not imply endorsement.
