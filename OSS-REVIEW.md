# OSS-REVIEW.md &mdash; Component Register

This file is the canonical record of every third-party open-source component
shipped with any simulator in this repository. It implements Document 3 of
the ISO/IEC 5230:2020 conformance pack maintained by Alin Li OÜ.

- **Repository:** https://github.com/Alin-Li-OU/Simulators
- **Publication URL:** https://alinli.com/simulators.html
- **First-party licence (all simulators):** Apache-2.0
- **Last reviewed:** 2026-05-31
- **Next scheduled review:** 2026-12-02
- **Review cadence:** Twice yearly on 2 February and 2 December
- **Reviewer:** Osama Abandeh, OSPO Lead
- **Contact:** [Compliance@alinli.com](mailto:Compliance@alinli.com)
- **Review-process diagram:** <https://alinli.com/oss/review-process.html>

## Decision register

| Component | Version | SPDX | Decision | Reviewer | Date | Rationale |
|---|---|---|---|---|---|---|
| _(none)_ | _-_ | _-_ | _-_ | _-_ | _-_ | No third-party OSS components are currently shipped. All simulators are self-contained single-file HTML documents using operating-system fonts only. |

## Per-simulator usage

| Simulator | Version | Third-party components |
|---|---|---|
| Alin Li Computer Explorer | 1.0.0 | None |
| Alin Li Git Simulator | 1.0.0 | None |
| Alin Li Linux Explorer | 1.0.0 | None |
| Alin Li NiFi Simulator | 1.0.0 | None |

## Notes

System fonts referenced in the simulators' CSS (Segoe UI, SF system fonts,
Tahoma, Consolas, Liberation Mono, and similar) are part of the user's
operating system. They are not redistributed by Alin Li OÜ and therefore
do not constitute third-party components for the purposes of this register
or of ISO/IEC 5230:2020.

## Re-review log

- **2026-05-31** &mdash; Pack v1.0: initial
  review and issuance. Programme scope set to the four interactive
  simulators published at alinli.com/simulators.html; first-party
  Apache-2.0; no third-party OSS components shipped at runtime
  (Osama Abandeh).
