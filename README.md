# ghost-workspace-hunter

**幽灵工作空间猎手** · SKILL.md skill

> WorkBuddy skill — purge stubborn timestamp-named "ghost workspaces" (`YYYY-MM-DD-HH-MM-SS` entries in the sidebar / `workspaces` table).

Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection.

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

## How to use / 如何使用

This is an **expert package / skill for the WorkBuddy AI assistant**.

**Prerequisites · 前置条件**
- WorkBuddy installed and signed in (latest version recommended).
- Prepare your own materials first (e.g. your literature library / course outline) — the agent works under a "stay faithful to the source, cite the page" rule.

**Import / enable · 导入 / 启用**
1. Download the package zip from this repo's **Releases**, or clone the repo; keep the `.codebuddy-plugin/` manifest intact.
2. In WorkBuddy, *custom connector → trust & enable*, or import the expert / enable the skill from the skill center.
3. Run one minimal example below to confirm the output matches your standards.

**Minimal example · 最小示例**
> 扫描并安全清理损坏的工作空间(先备份、走回收站)。


**Portability · 可移植性** — Delivered for WorkBuddy; won't run as-is elsewhere, but the methodology is documented in plain text and can be re-implemented on another platform. Knowledge is portable even if the runtime isn't.

**More · 更多**
Full onboarding & per-line guidance: portal [Lucewalk Lumen · 沐光行客](https://github.com/Lucewalk-Lumen/about-me) → "How to use". Issues: open one on this repo.
