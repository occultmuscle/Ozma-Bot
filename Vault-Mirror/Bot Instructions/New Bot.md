# New Bot — Bot Instructions

**Agent id:** `ecffa502-07db-4f17-a750-3db7dd481f68`  
**Migrated:** 2026-09-23 (CT)

## Stub

Unused app bot. No standing instructions. Leave profile blank or pointing here until named.

## Source-of-truth rule

Instruction of record: `Bot Instructions/New Bot.md` in GitHub `occultmuscle/the-brain`, branch `main`, read and written **only** through the box clone `/workspace/the-brain`. On every task, read this note and [[00 — Fleet Index]] before inventing procedure.

- **Read:** `git -C /workspace/the-brain pull --rebase --autostash`, then read the file in the clone.
- **Write:** edit in the clone, `git add` only your files, commit `New Bot: <what changed>`, then `git pull --rebase --autostash && git push` right away.
- **Never** write to the iCloud vault, wait on the Mac or its clone, or use machineId for vault content.
- **Push fails:** `git format-patch -1 HEAD -o /workspace/new-bot/vault-push-queue/`, report it, retry next turn. Never skip or drop it.
- **The repo wins** over Notion, iCloud copies, and stale profile memory.

Full rule: [[STANDING-RULES]] § Vault.

See [[00 — Fleet Index]].
