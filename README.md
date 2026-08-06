# WaefreBeorn Umbrella License v3.0

Canonical home of the **WaefreBeorn Umbrella License v3.0**, the source-available
license governing all WaefreBeorn projects — AGI operating systems, native C11
inference engines, video editors, office suites, AI agents, creative works,
firmware, and all associated tool repos.

**~ WuBu ~ is the space. This is WaefreBeorn.**

**Anyone may use this license for THEIR work.** Copy it into your repo,
adopt it, and your work joins the ~ WuBu ~ space. See §0 of the LICENSE.

## Why this exists

> "there is no such thing as third party if we can properly make the code"

The umbrella license lets every downstream repo pin a stable, hash-verifiable copy
rather than copy-pasting license text into each one. A repo may carry either the
full text or a pointer — the pointer points to this repository.

The license is **agnostic** — it applies to all WaefreBeorn work regardless of medium:
source code, binary blobs, model weights, datasets, documentation, videos, music,
art, comics, hardware designs, and any future medium we invent.

## Contents

| File                 | Description                                                        |
|----------------------|-------------------------------------------------------------------|
| `LICENSE`            | Canonical WaefreBeorn Umbrella License v3.0 full text              |
| `LICENSE_POINTER`    | The one-paragraph pointer other repos may use instead of the full text |
| `FAQ.md`             | Frequently-asked questions (commercial use, compliance, …)       |

## Quick reference

- **Type:** custom source-available (NOT OSI / NOT FSF approved)
- **Commercial use:** The Populace (individuals, non-profits, governments, <100 FTE / <$1M revenue) are free. Mega-corporations ($100M+ revenue) must follow Corporate Obligations.
- **Attested-mutation clause:** every self-modification is measured into a firmware PCR (or equivalent audit log) — never silently applied
- **SPDX-Identifier:** `WaefreBeorn-Umbrella-3.0`
- **Contact:** waefrebeorn@waefrebeorn.org

## Using the license

```cmake
# CMake — fetch a pinned copy
FetchContent_Declare(
  waefrebeorn-license
  GIT_REPOSITORY https://github.com/waefrebeorn/waefrebeorn-umbrella-license.git
  GIT_TAG        v3.0.0
)
```

or in a repo, `LICENSE`:
```
SPDX-License-Identifier: WaefreBeorn-Umbrella-3.0
```

## The Five Freedoms (Populace)

1. **Use** — for any purpose, no permission needed
2. **Modify** — adapt for any lawful purpose
3. **Distribute** — redistribute in any medium
4. **Sell** — keep all revenue, no royalty owed
5. **Integrate** — into any system or platform

## Corporate Obligations

- **Attribution** (Obligation A) — prominent credit required
- **Fair MaaS** (Obligation B) — $20M+ MaaS revenue requires commercial agreement
- **Copyleft at Scale** (Obligation C) — $1M+ FTE or revenue: publish derivatives under same license
- **Anti-Circumvention** (Obligation D) — affiliate shell revenue aggregation

## Prohibited Activities

Real-time mass surveillance · censorship · autonomous weapons · discrimination ·
fraud/identity theft · illegal activity · shell-entity evasion · malicious compliance.

## Repositories covered

### Core Infrastructure
- `waefrebeorn/WuBuOS` — Hybrid AGI operating system (C11, TempleOS/ZealOS heritage)
- `waefrebeorn/WuBuOffice` — Native C11 SLERM of OOXML office suite
- `waefrebeorn/WuBuPad` — C11 code editor (Notepad++ feature parity)
- `waefrebeorn/WuBuMath` — Pure C11 math & media encoding library
- `waefrebeorn/WuBuMedia` — Stream-native media representation layer
- `waefrebeorn/wubufw-tools` — UEFI firmware tooling (mkpe / mkesp)

### Creative / Media
- `waefrebeorn/wubuedit` — Native C11 AGI video editor (Vegas 8 SLERM)
- `waefrebeorn/WuBuWizard` — Best C11 recursive-inference engine
- `waefrebeorn/WuBuVideo` — AI video generation pipeline
- `waefrebeorn/WuBuWallPaper` — MP4/GIF wallpaper engine
- `waefrebeorn/WuBuCut` — Open-source CapCut alternative
- `waefrebeorn/WuBuSkills` — AI agent skills by NVIDIA
- `waefrebeorn/WuBuRouter` — Unlimited FREE AI coding router
- `waefrebeorn/seymour-winswritten` — Meme art clipart books

### SLERM Projects
- `waefrebeorn/slermes` — Pure C11 reimplementation of Hermes Agent
- `waefrebeorn/slermes-odyssey` — Self-hosted AI workspace
- `waefrebeorn/slerm_spacewasm` — Flight-compliant WASM interpreter

### Tools & Utilities
- `waefrebeorn/WuBuContainer` — Universal WuBu file format
- `waefrebeorn/WuBuFX` — OBS Studio StreamFX port (GPL-2.0 derivative)
- `waefrebeorn/WuBu-DLP` — yt-dlp GUI wrapper
- `waefrebeorn/grahaos_audit` — AI OS audit
- `waefrebeorn/KAN-WuBu-Memory` — AI character interaction system
- `waefrebeorn/mediaremux` — MKV remuxer
- `waefrebeorn/ghost` — Paranormal detection system

### Special Cases
- `waefrebeorn/WuBu-DefCon` — Autonomous red teaming (AGPL-3.0)

> Any work published under the WaefreBeorn name that is not listed here is still
> covered by this license. The list is illustrative, not exhaustive.

## Design Research Corpus

- `/home/wubu/wubu_design_refs/` — 104 design documents, HCI studies, NLE UI analysis
- `/home/wubu/wubuwizard/wubuedit/` — Primary AGI video editor development workspace

## Governance

Future versions (v3.1, v4.0, etc.) may be published through a publicly documented
governance process. Users may continue under their original version or upgrade.
See §11 (Modifiable License Reserve) for the research-backed modification framework.

## The Penny Clause (§14)

Every user of WaefreBeorn Work owes the Licensor one **physical** penny sent by
**physical mail**. Not digital, not crypto, not QR codes — real metal. The only
exception: if total pennies owed exceed shipping weight limits, excess may be
digital. But you always start with one real penny. This is a whimsical
proof-of-read mechanism (like the M&M's trick at concerts). If you've read
this far, grab a penny and put it in an envelope. Do it now.
See §14 of the LICENSE for details.