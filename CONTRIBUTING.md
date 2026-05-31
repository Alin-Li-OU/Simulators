# Contributing to Alin Li Simulators

Welcome, and thank you for considering a contribution.

This repository hosts the educational simulators of Alin Li OÜ (Estonia).
First-party code is licensed under the **Apache License 2.0**.
Third-party open-source components, if and when they are added, are
managed under our open-source compliance programme, which is
self-certified to **ISO/IEC 5230:2020** (OpenChain).

## Current dependency posture

The simulators in this repository **do not bundle or load any third-party
open-source components at runtime**. They are self-contained single-file
HTML documents that use operating-system fonts only.

Please keep it this way unless there is a strong reason otherwise. If
you must add an open-source component, follow the policy below.

## Open-source policy summary

The full policy is maintained in the Alin Li OÜ internal intranet under
*Staff Resources &rsaquo; Compliance &rsaquo; OSS Policy*. The operational
rules for contributors are:

### 1. Permitted licences

Components carrying any of the following SPDX licences may be added to a
simulator without prior approval, provided they are reviewed per
section 3 below:

- `MIT`, `BSD-2-Clause`, `BSD-3-Clause`, `Apache-2.0`, `ISC`, `Zlib`
- `MPL-2.0`
- `OFL-1.1` (fonts only)

### 2. Review-required licences

Components under these licences require explicit OSPO Lead approval
before merging:

- `LGPL-2.1`, `LGPL-3.0`
- `EPL-2.0`, `CDDL-1.0`
- `CC-BY-4.0`, `CC-BY-SA-4.0` (non-software assets only)

### 3. Formal-approval licences

Components under these licences are permitted only with a written
compliance plan from the OSPO Lead:

- `GPL-2.0`, `GPL-3.0`, `AGPL-3.0`
- `SSPL`, `BUSL`, `Commons-Clause`
- Any "source-available" licence not recognised by OSI.

### 4. Forbidden by default

Components with no discoverable licence, multiple conflicting licences,
or licences not listed above, may **not** be added until the OSPO Lead
has reviewed them.

## Review procedure for new components

When you add a new direct dependency:

1. Confirm the licence is on the Permitted list.
2. Add a row to [`OSS-REVIEW.md`](./OSS-REVIEW.md) describing the
   component, version, SPDX identifier, your initials, and the date.
3. Regenerate the affected simulator&rsquo;s `credits/<slug>.html` and
   `sbom/<slug>.cdx.json`.
4. Update the top-level `NOTICE` to reflect the new component.

## Outbound contributions

If you intend to contribute code from this repository back to an upstream
open-source project, contact the OSPO Lead first ([Compliance@alinli.com](mailto:Compliance@alinli.com))
for a brief approval.

## OSPO contact

- **OSPO Lead:** Osama Abandeh
- **Email:** [Compliance@alinli.com](mailto:Compliance@alinli.com)
- **Public conformance statement:** <https://alinli.com/oss/conformance.html>
- **Review process diagram:** <https://alinli.com/oss/review-process.html>
- **Review cadence:** Twice yearly on 2 February and 2 December
