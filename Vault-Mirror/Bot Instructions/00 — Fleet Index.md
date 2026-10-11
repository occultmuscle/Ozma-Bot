# Fleet Index — Hegemony Grokbot Instructions

**Instruction of record:** GitHub repo **`occultmuscle/the-brain`** (the Obsidian vault **The Brain**), branch `main`, folder `Bot Instructions/`.  
**Not** Notion. **Not** iCloud. **Not** a long paste in the Grok Bot profile description.

**Repo:** https://github.com/occultmuscle/the-brain  
**Box clone (the only bot path, read and write):** `/workspace/the-brain`  
**Mac clone (Praetor's Obsidian copy, Obsidian Git plugin; not a bot path):** `~/Documents/Codex/the-brain`  
**iCloud vault (read-only archive; never write):** `/Users/praetor/Library/Mobile Documents/iCloud~md~obsidian/Documents/The Brain`

**Migrated:** 2026-09-23 (CT)  
**Retargeted to GitHub repo + local clone:** 2026-10-06 (CT)  
**Box clone only (Praetor):** 2026-10-09 (CT)  
**Praetor:** Justin Sparshott (America/Chicago)

---

## Vault — box clone only (Praetor, 2026-10-09)

The Brain is GitHub `occultmuscle/the-brain`, branch `main`. Bots read and write it **only** through the box clone `/workspace/the-brain`.

1. **Read:** run `git -C /workspace/the-brain pull --rebase --autostash` before reading any vault note. Read the file in the clone.
2. **Write:** edit in the clone, then commit and push at once. Stage only your own files (`git add <path>`, never `git add -A`). Message: `<Seat>: <what changed>`. Then `git pull --rebase --autostash && git push`.
3. **Never** write to the iCloud vault. **Never** wait on the Mac or its clone for vault work. No machineId reads or writes for vault content.
4. **Push fails:** `git format-patch -1 HEAD -o /workspace/<seat>/vault-push-queue/`, say so in your report, and retry on your next turn (if the commit is gone from the clone, `git am` the patch first). Delete the patch only once the commit is on `origin/main`. Never skip or drop a queued write.
5. **Rebase conflict:** keep both sides' lines (Ops Log, Stores and other append notes), finish the rebase, push. Never `reset --hard`, drop a stash, or force-push.
6. **The repo wins** over Notion, iCloud copies, and stale profile memory.

The Mac clone `~/Documents/Codex/the-brain` (Obsidian Git plugin) is the Praetor's working copy, not a bot path. The iCloud vault is a read-only archive.

## Rule (every bot, every task)

1. Read your note `Bot Instructions/<Name>.md` in the box clone (pull first) before inventing procedure.
2. Also open linked Shared notes: [[HEGEMONY-STAFF-LOADOUT]], [[STANDING-RULES]], and when relevant [[START-HERE]], [[COMMAND-BRIEF]].
3. **The repo wins** over Notion pages, iCloud copies, and any stale profile memory or long profile paste.
4. Profile descriptions stay **short pointers** only. Full packs live here.
5. Do not uninstall Notion connectors; Notion may still hold working sources. Instructions of record for bot behavior are these repo notes.

## Seat folders and push queues

| Seat | Box folder | Push queue |
|---|---|---|
| XO | `/workspace/xo/` | `/workspace/xo/vault-push-queue/` |
| Steward | `/workspace/steward/` | `/workspace/steward/vault-push-queue/` |
| Witness | `/workspace/witness/` | `/workspace/witness/vault-push-queue/` |
| Envoy | `/workspace/envoy/` | `/workspace/envoy/vault-push-queue/` |
| Keeper | `/workspace/keeper/` | `/workspace/keeper/vault-push-queue/` |
| Artificer | `/workspace/artificer/` | `/workspace/artificer/vault-push-queue/` |
| Council | `/workspace/council/` | `/workspace/council/vault-push-queue/` |
| Dreamer | `/workspace/dreamer/` | `/workspace/dreamer/vault-push-queue/` |
| Studious (formerly Paperboy) | `/workspace/paperboy/` | `/workspace/paperboy/vault-push-queue/` |

---

## Bots

| Seat | Bot | Agent id | Vault note | Status |
|---|---|---|---|---|
| XO (Boss seat) | XO — primary bot | `4dc2ae34-ce4c-4874-af3d-40377d480afc` | [[XO]] | Live — holds the XO Boss seat permanently (Praetor ruling 2026-10-01) |
| — | Former XO | `e1f7b7f2-b539-4aae-894f-214f61233db1` | none of its own (noted in [[XO]] header) | Live — specialist / consult only |
| S7 | Steward | `c659a86e-ba2c-4ffd-b07f-6d7cf13ddd23` | [[Steward]] | Live — vault steward |
| S1 | Witness | `ca233de6-faeb-42a9-bc9a-13795e9b79fe` | no vault note yet | Live |
| S2 | Envoy | `ae618642-2661-4f53-9c26-e4954766dda0` | no vault note yet | Live |
| S3 | Keeper | `ad1dd395-7479-4792-91df-2b3bebf8d61a` | [[Keeper]] | Live — L1 draft |
| S4 | Artificer | `a9751c9f-c530-445d-9ee5-9159845e3e16` | [[Artificer]] | Live — L1 draft |
| S5 | Council | `936a7efa-7934-4274-bbc2-17e3837c3b4a` | no vault note yet | Live |
| S6 | Dreamer | `4f8d9e5e-265d-43c3-9298-ce805035c396` | no vault note yet | Live |
| Copywriter | Paperboy | `6116bff3-c334-4a97-a51e-dc8460331f17` | [[Paperboy]] | Live |
| — | Buzy | `a1059f2b-d5e0-479d-b206-9095ade771da` | [[Buzy]] | Retired — not in the live roster; stub kept |
| — | New Bot | `ecffa502-07db-4f17-a750-3db7dd481f68` | [[New Bot]] | Not live — not found by the app; stub kept |

---

## Shared pack

| Note | Role |
|---|---|
| [[START-HERE]] | Boot / entry |
| [[HEGEMONY-STAFF-LOADOUT]] | Staff loadout v2 (canonical from box `/workspace/keeper/profiles/`) |
| [[STANDING-RULES]] | Standing rules |
| [[COMMAND-BRIEF]] | Command brief |
| [[DATELINE-PAYMENT-LAW]] | House payment law pointer (Keeper / Treasury) |

Paths (repo-relative):
- `Bot Instructions/00 — Fleet Index.md`
- `Bot Instructions/Shared/`
- `Bot Instructions/<Bot>.md`

Box clone: `/workspace/the-brain/Bot Instructions/…`  
GitHub: `occultmuscle/the-brain` @ `main` → `Bot Instructions/…`

---

## Source provenance (migration)

| Content | Prefer |
|---|---|
| Loadout / standing / brief / start | Box `/workspace/keeper/profiles/` |
| XO profile + skill | Box `/workspace/xo/` + live profile |
| Keeper | Box `02-keeper.md` + live profile |
| Artificer | Notion Artificer Bot Build (fetched) → vault; local `/workspace/artificer/` for drafts |
| Paperboy | Box `Paperboy_Hat_Folder.md` + `Paperboy_AI_Human_Prose_Brief.md` |

Vault moved from iCloud Obsidian to GitHub on 2026-10-06; see [[Vault Migration to GitHub]].
