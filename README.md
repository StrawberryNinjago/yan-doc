# yan-doc

Yan’s agreed documentation standards for presentations, requirements, design documents, procedures and handoffs.

- Start with the reader, intended outcome and narrative flow.
- Use concrete examples, concise bullets and explicit human ownership.
- Preserve agreed decisions; distinguish evidence from proposed improvements.
- Check meaning and rendered layout separately.

## Download and use at work

[Download the ZIP](https://github.com/StrawberryNinjago/yan-doc/archive/refs/heads/main.zip), or clone the repo:

```sh
git clone https://github.com/StrawberryNinjago/yan-doc.git
```

The reusable instructions are in [`skills/yan-documentation-standards/SKILL.md`](skills/yan-documentation-standards/SKILL.md). Open the downloaded repo in your coding assistant, or attach that file to a conversation, then ask:

> Read `skills/yan-documentation-standards/SKILL.md` and apply it to this document. Show the proposed structure and wording first; do not edit until we align.

Supply the document, audience, intended outcome and any approved examples. The skill provides documentation standards, not application context. Use your employer-approved assistant and follow company policy for work materials.

This file can be supplied as context without installing a slash command. Automatic skill discovery and command names depend on the assistant; the short `/yan-doc` command below is for OMP.

## Install `/yan-doc` in OMP

From the downloaded repo, run these commands in a macOS/Linux shell. `cp -i` asks before replacing an existing installation.

```sh
mkdir -p "$HOME/.agents/skills/yan-documentation-standards" "$HOME/.omp/agent/commands"
cp -i skills/yan-documentation-standards/SKILL.md "$HOME/.agents/skills/yan-documentation-standards/SKILL.md"
cp -i commands/yan-doc.md "$HOME/.omp/agent/commands/yan-doc.md"
```

Reload OMP’s skills and commands, or start a new session. Then use:

```text
/yan-doc Review this design document. Show a plan before editing.
```

The shortcut loads the full standard from `~/.agents/skills/yan-documentation-standards/SKILL.md`. It does not depend on the original conversation or this repo’s checkout location.

## Update

For a cloned repo, pull the latest version:

```sh
git pull --ff-only
```

Then repeat the installation commands if using OMP. For a ZIP download, download the latest ZIP again.

Installed copies do not synchronize automatically. To publish an agreed improvement, update this repo’s skill or command file, then commit and push. Keep project-specific facts, tickets, screenshots and secrets outside this repo.

## Initial publication

- The agreed documentation standard, unchanged from the local version.
- The OMP `/yan-doc` shortcut.
- Download, installation and usage instructions.
