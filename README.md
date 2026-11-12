# gpty-knowledge-base

The bundled gPTY wiki layout for [gpty](https://github.com/godot-pty/gpty) — a gpty plugin shipping one profile: a full-grid Wiki pane opened on the shipped vault.

## Install

    gpty plugin install godot-pty/gpty-knowledge-base

Installation clones this repo, validates `gpty-plugin.toml` with the shipped validator, and asks a human to review it in the gpty GUI before anything installs — a plugin's content runs as you, so acceptance is explicit and pinned to the revision you reviewed. A newer revision asks again.

## Layout

- **Knowledge Base** — a Wiki pane in preview mode, opening `index.md` from the bundled vault (`vault_path = "@knowledge"`, resolved to a copy in your user data).

The app ships the same layout as a seeded default on a fresh install. Installing this plugin while that copy exists asks to replace it; confirming gives the name to the plugin-owned copy, which can then be uninstalled from its sidebar trash.

The profile names no program, so activation does not raise a Workspace Trust dialog.
