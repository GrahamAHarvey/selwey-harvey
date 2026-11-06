# Changelog

Each entry records what changed, which component changed, the date, and the type of change:

- **Editorial** — wording, formatting or presentation, with no change in meaning.
- **Technical** — structure, metadata, tooling or distribution, with no change in meaning.
- **Substantive** — a change to what SHOP, SHPN or the framework says or requires.

Components: Package, SHOP, SHPN, Framework, Skill, Metadata.

---

## Package release 1.0.0 — 2026-11-05

First release of the Selwey-Harvey Operational Package.

| Component | Change | Type |
| --- | --- | --- |
| Package | README rewritten as the package landing page: identity, problems addressed, contents, discovery identifiers, ways to use the package, navigation, versioning. Existing Engage, Support, Attribution and License sections retained. | Technical |
| Package | Added CHANGELOG.md. | Technical |
| Package | README intended audience set to agents primarily, as a designated deployment tool for agents; metadata `audience` field added. | Editorial |
| Package | Removed an internal "EDIT THIS LINE" HTML comment from `docs/support.html`; no visible change. | Technical |
| Metadata | Added `metadata/package.yaml` (metadata version 1.0.0). | Technical |
| Skill | Added Agent Skill `skill/selwey-harvey-shop/SKILL.md` (Skill version 1.0.0). | Technical |
| SHOP | Version 1.0 → 1.1 (Nov 5 2026). Step 6 now reads "state that the transaction is operating from it" in place of "state that you operate from it", so per-decision disclosure is distinct from an SHPN declaration. | Substantive |
| SHPN | Version 1.0 → 1.1 (Nov 5 2026). Membership section: non-members "do not receive" (previously "do not participate in") the network's information-sharing or consideration advantages, so per-decision users can still report observed conduct to the network. | Substantive |
| SHOP, SHPN | Header lines normalised to "Version 1.1 — November 5, 2026" (SHPN previously "Draft — November 4, 2026"; SHOP previously had no header line). | Editorial |
| Framework | Version 1.01 → 1.02 (Nov 5 2026). Header date labelled "Original writing — September 16, 2026"; "Working draft" retained. No change to content. | Editorial |

Substantive changes in this release are limited to SHOP step 6 and the SHPN Membership sentence above. The framework's content is unchanged.

## Prior history

Before package release 1.0.0, the repository held the framework, SHOP and SHPN documents and the support page (`docs/support.html`). That history is recorded in the repository's commit log.
