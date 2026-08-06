# Waefrebeorn Umbrella License v3.0 — FAQ

## Is this OSI/FSF-approved?

No. It is a custom source-available license. The source is visible and
redistributable for the Populace (individuals, non-profits, governments,
small businesses) without restriction. Mega-corporations must follow
the Corporate Obligations (§4) but still have access — no permission needed.

## Can I use this in my project?

**Yes** — for any purpose that is not a Prohibited Activity (§1.10):
- Personal / research / educational use: fully free (Freedom 0–4)
- Government use: explicitly covered (§7)
- Commercial use by Populace (<100 FTE / <$1M revenue): fully free
- Commercial use by Corporations: covered by Corporate Obligations
  (attribution + revenue thresholds), **no permission required** —
  just follow the obligations

**No** — for prohibited activities: real-time mass surveillance, censorship,
autonomous weapons, discrimination, fraud, or illegal activities.

## What is the "attested-mutation" clause?

Any self-modification of code published under this license, when executed
under WuBuFW, **must** extend the firmware PCR bank (PCR4 for code-as-data)
before the mutation is committed. Where no firmware attestation is
available, the mutation must be appended to the WuBuOS recursive-optimizer
audit log (`dgm_archive.json`) so it is reproducible.

## Does this cover models, video, art, firmware — not just code?

**Yes, absolutely.** This license is **agnostic**. It covers ALL Waefrebeorn Work:
- Source code and binaries
- Model weights, LoRAs, merged models, fine-tunes
- Datasets, training data
- Videos, music, images, comics, clipart
- Documentation, research papers
- Hardware designs, UEFI firmware
- Configurations, scripts
- Any future medium we invent

This is an umbrella license. It is NOT about "MaaS" (Model as a Service).
It is about ALL things we make, in ALL media, across ALL platforms.

## Do I need to ship the full license?

A repo may ship either the full `LICENSE` text or the short
`LICENSE_POINTER` that references
https://github.com/waefreborn/waefrebeorn-umbrella-license.

## Commercial licensing

Commercial licenses are NOT required — the license is source-available
with obligations, not restricted. Corporations using Waefrebeorn Work
commercially simply follow the Corporate Obligations in §4. A commercial
license is only needed if you want to waive the obligations entirely
(attribution, copyleft-at-scale, MaaS threshold).

## Do I have to send a penny?

YES — a **physical** penny sent by **physical mail**. Not digital pennies,
not cryptocurrency, not QR codes, not NFTs, not virtual points. Only real
metal. Section 14 of the license requires one physical penny per use,
derivative, or redistribution. The only exception: if the total pennies
owed exceeds what can be physically shipped in one package (weight
restrictions), the excess may be sent as a digital payment — but you
must always start with at least one real physical penny first. If you've
read this far, grab a penny and put it in an envelope. Do it now.

## How does the MaaS threshold work?

**Obligation B (Fair Commercial Terms for MaaS)**: Any Corporation operating
a MaaS (Model as a Service) business using Waefrebeorn Work, with aggregate
revenue exceeding $20,000,000 USD over any consecutive 12 months, must enter
into a commercial agreement with the Licensor before using Waefrebeorn Work
for MaaS purposes.

**This is just ONE obligation among four.** The license covers much more
than MaaS — it covers all Waefrebeorn output in all media. MaaS is simply
one of the four corporate obligations because it's where mega-corporation
exploitation risk is highest.