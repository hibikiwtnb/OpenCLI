# Agent rules for this fork

This repository is a public fork. Everything committed here is world-readable,
including commit messages, branch names, and file names.

- Never commit host-specific details: absolute local paths, user or host names,
  IP addresses, private project names, account emails, internal URLs, or secrets.
- Keep machine-specific settings out of the code. Read them from local config
  instead, e.g. `~/.opencli/browser-launcher.json` (`start`, `profileDir`).
- Use generic branch names and commit messages that describe the change, not the
  machine it was made for.
- Before every push, grep the staged diff for local paths, host names, and
  addresses, and remove anything that only makes sense on one machine.
