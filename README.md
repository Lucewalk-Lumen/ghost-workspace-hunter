# ghost-workspace-hunter

**幽灵工作空间猎手** · SKILL.md skill

> WorkBuddy skill — purge stubborn timestamp-named "ghost workspaces" (`YYYY-MM-DD-HH-MM-SS` entries in the sidebar / `workspaces` table).

Part of the [Lucewalk Experts](https://github.com/Lucewalk/lucewalk-experts) collection.

## What it does

- Hunts residual timestamp-named workspaces that keep re-appearing after deletion;
- **Reversible by design** — targets move to Trash/Recycle Bin, never hard-deleted;
- **Database backup first** — the WorkBuddy DB is backed up before any change;
- **Active-session guard** — running sessions are protected;
- **Never touches real named workspaces** — only timestamp-pattern entries match.

## How it works

- Cross-platform (macOS / Windows);
- `SKILL.md` declares the trigger conditions; `scripts/cleanup.py` performs the guarded cleanup;
- Summon it in WorkBuddy, confirm the targets, run.

## Install

Copy the skill folder into your WorkBuddy skills directory (keeping `SKILL.md` at its root) and enable it.

## License

MIT — see [LICENSE](LICENSE) in the collection hub.
