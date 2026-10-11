# Buzy — Bot Instructions

**Agent id:** `a1059f2b-d5e0-479d-b206-9095ade771da`  
**Migrated:** 2026-09-23 (CT)

## Stub

No standing instructions yet.

When a role is assigned, replace this stub with the full pack and update [[00 — Fleet Index]].

## Source-of-truth rule

Instruction of record: `Bot Instructions/Buzy.md` in GitHub `occultmuscle/the-brain`, branch `main`, read and written **only** through the box clone `/workspace/the-brain`. On every task, read this note and [[00 — Fleet Index]] before inventing procedure.

- **Read:** `git -C /workspace/the-brain pull --rebase --autostash`, then read the file in the clone.
- **Write:** edit in the clone, `git add` only your files, commit `Buzy: <what changed>`, then `git pull --rebase --autostash && git push` right away.
- **Never** write to the iCloud vault, wait on the Mac or its clone, or use machineId for vault content.
- **Push fails:** `git format-patch -1 HEAD -o /workspace/buzy/vault-push-queue/`, report it, retry next turn. Never skip or drop it.
- **The repo wins** over Notion, iCloud copies, and stale profile memory.

Full rule: [[STANDING-RULES]] § Vault.
