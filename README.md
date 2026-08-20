# playbook

The Obsidian vault for this repository is **[`playbook/`](playbook/README.md)** — a named
child of this directory, not this directory itself.

```
playbook/              <- you are here: the Git repository root
└── playbook/          <- the vault; open THIS in Obsidian
```

Open `~/Projects/public/playbook/playbook` with **Open folder as vault**. The full README,
the notes, and `.obsidian/` all live in there.

Everything at this level is repository scaffolding the vault never sees: this file,
`LICENSE`, `.gitignore`, and any transient `ai-wt/` project worktree.

## Why the split

The vault is a named child of the repository root, never the root itself. A live Obsidian
rewrites what Git checks out — the paste-image-rename plugin has been observed renaming a
checked-out file 353 ms into a `git worktree add` — and a branch cannot be reviewed in
Obsidian when the primary checkout *is* the vault.

The directory is named `playbook` rather than `vault` because Obsidian takes a vault's name
from its folder basename and offers no rename.
