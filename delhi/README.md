# 🏛️ `/delhi/` — The Ancestor's Room

This folder preserves the **ETHGlobal New Delhi 2025** ancestor of the OSO
P.I.T. — the hackathon build where the pit first got its name
(**🏆 Most Creative Use of ENS**), plus the grown repositories it became.

**Read the room (pretty version):** https://osopit.com/delhi/

## Contents

| File | What it is |
|---|---|
| `index.html` | the Ancestor's Room — story, architecture, builders, downloads |
| `osopit-cradle-grmkris-snapshot.tar.gz` | source snapshot of the original hackathon build (grmkris/eth-global-new-delhi-2025-opensource-orchestra), minus one accidentally-committed 77 MB AWS CLI installer; full history lives on at the origin remote |
| `osopit-platform-opensource-orchestra.bundle` | git bundle of opensource-orchestra/osopit — the grown monorepo (152 commits, all branches/tags) |
| `osopit-ens-contracts.bundle` | git bundle of opensource-orchestra/osopit-ens — the Durin L2 ENS contracts |
| `opensource-orchestra-org-site.bundle` | git bundle of opensource-orchestra/opensource-orchestra — the org site |
| `README-ancestor.md` | the platform repo's own README, copied for easy reading |
| `img/` | the ancestor's own artwork, downscaled for the web — the visual pit, the stage, the backdrop, the six stand-holders (full-resolution originals inside the cradle snapshot) |

## Resurrect it yourself

```bash
# a git bundle is a whole repository — full history inside one file
git clone osopit-platform-opensource-orchestra.bundle osopit
cd osopit && git log --oneline | tail   # history all the way back

# the cradle is a plain snapshot
tar -xzf osopit-cradle-grmkris-snapshot.tar.gz
```

## Living remotes (all public, all CC0)

- 🌱 cradle: https://github.com/grmkris/eth-global-new-delhi-2025-opensource-orchestra
- 🏗️ platform: https://github.com/opensource-orchestra/osopit
- 📛 contracts: https://github.com/opensource-orchestra/osopit-ens
- 🌐 org site: https://github.com/opensource-orchestra/opensource-orchestra
- 🏆 laurel: https://ethglobal.com/showcase/opensource-orchestra-y1egw
- 📜 restoration doc: https://publicinform.com/osopit/

*Archived with love 2026-09-23 · the equinox wave 🌗 · CC0 · the pit provides 🕳️🎻*
