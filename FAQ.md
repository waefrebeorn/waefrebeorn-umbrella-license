# WaefreBeorn Umbrella License v3.0 — FAQ

## Is this OSI/FSF-approved?

No.  It is a custom source-available license.  The source is visible and
redistributable for non-commercial use, but commercial licensing is gated
on explicit written permission.

## Can I use this in my project?

Yes, for non-commercial / personal / research / educational purposes,
provided you retain attribution and the attested-mutation clause applies
to any modified fork that runs under WuBuFW.  For commercial use, contact
waefrebeorn@waefrebeorn.org.

## What is the "attested-mutation" clause?

Any self-modification of code published under this license, when executed
under WuBuFW, **must** extend the firmware PCR bank (PCR4 for code-as-data)
before the mutation is committed.  Where no firmware attestation is
available, the mutation must be appended to the WuBuOS recursive-optimizer
audit log (`dgm_archive.json`) so it is reproducible.

## Do I need to ship the full license?

A repo may ship either the full `LICENSE` text or the short
`LICENSE_POINTER` that references
https://github.com/waefreborn/waefrebeorn-umbrella-license.

## Commercial licensing

Commercial licenses are available.  They lift clauses 4 (commercial use),
6 (attested-mutation logging), and the attribution-fragment retention
requirements, while keeping the liability disclaimer.
