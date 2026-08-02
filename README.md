# WaefreBeorn Umbrella License v3.0

Canonical home of the **WaefreBeorn Umbrella License v3.0**, the source-available
license governing the WuBuFW custom UEFI firmware, the WuBuOS AGI operating system,
the WuBuWizard C11 inference substrate, and all associated tool repos.

## Why this exists

> "there is no such thing as third party if we can properly make the code"

The umbrella license lets every downstream repo pin a stable, hash-verifiable copy
rather than copy-pasting license text into each one.  A repo may carry either the
full text or a pointer — the pointer points to this repository.

## Contents

| File      | Description                                                        |
|-----------|-------------------------------------------------------------------|
| `LICENSE` | Canonical WaefreBeorn Umbrella License v3.0 full text              |
| `LICENSE_POINTER` | The one-paragraph pointer other repos may use instead of the full text |
| `FAQ.md`  | Frequently-asked questions (commercial use, compliance, …)       |

## Quick reference

- **Type:** custom source-available (NOT OSI / NOT FSF approved)
- **Commercial use:** requires explicit written permission from WaefreBeorn
- **Attested-mutation clause:** every self-modification is measured into a
  firmware PCR (or equivalent audit log) — never silently applied
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
SPDX-License-Identifier: WaefreBeorn-UMV3
```

## Repositories covered

- `waefreborn/WuBuOS` — AGI operating system runtime
- `waefreborn/WuBuFW` — custom UEFI firmware substrate
- `waefreborn/WuBuWizard` — C11 recursive-inference engine
- `waefreborn/wubufw-tools` — mkpe / mkesp / tooling
