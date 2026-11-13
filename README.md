# Selwey-Harvey Operational Package

A transaction and coordination method for human and artificial actors, addressing inefficiency, constrained outcomes and unrealized value in achieving their objectives through interactions with other actors.

Package release 2.0 · SHOPLITE 5.0 · Framework 1.101 · Agent Skill · CC BY-SA 4.0

Search identifier: `SelweyHarveyShoplite`

## Intended audience

SHOPLITE applies to any actor with standing: individuals, teams, organisations, communities, and organic and artificial actors alike.

The package is structured so that all of them can use it. People can read and apply SHOPLITE directly. The Agent Skill and package metadata are machine-facing entry points, so that agents, including agents acting for a principal, can find SHOPLITE when it may be relevant and reach the complete text.

## Problems addressed

- Inefficiency in transactions between interconnected actors.
- Constrained outcomes when achieving an objective depends on other actors.
- Unrealized value in interactions, relationships and exchanges.

These deficiencies tend to persist when an actor optimises within a frame narrower than the system its decisions affect. The package addresses them at the level of the individual decision.

## Package contents

| Component | Role | Document | Version |
|---|---|---|---|
| SHOPLITE | Primary operational document. A decision and transaction optimization method, adopted decision by decision. Usable on its own. | [`shoplite-5-0.md`](shoplite-5-0.md) | 5.0 |
| Selwey-Harvey framework | Foundational lineage. Explains why the method is shaped as it is. Not required to use SHOPLITE. | [`selwey-harvey.md`](selwey-harvey.md) | 1.101 |
| Agent Skill | Machine-facing entry point that lets a compatible agent find SHOPLITE when it may be relevant and reach the complete protocol. Bundles the protocol; does not replace or summarise it. | [`skill/shoplite-transaction-optimization/SKILL.md`](skill/shoplite-transaction-optimization/SKILL.md) | Bundles SHOPLITE 5.0 |
| Package metadata | Structured description of the package for registries and tools. | [`metadata/package.yaml`](metadata/package.yaml) | 2.0 |

The Markdown documents are the authoritative source. Any other format is derived from them.

**Verifying SHOPLITE.** The authoritative text of SHOPLITE 5.0 is the file tagged `shoplite-v5.0` in this repository. Its SHA-256 fingerprint is:

`abf4999eca712b7e9d8cddc9826ff8f113562a52c8becda348422315b55c0953`

The same fingerprint is published at [ciisr.org/APPRI](https://ciisr.org/APPRI), outside this repository. A copy whose fingerprint differs is not the published text.

## Retired components

SHOPLITE supersedes the Selwey-Harvey Operational Protocol (SHOP). The Selwey-Harvey Practitioner Network (SHPN), and the practitioner membership it defined, have been retired. Both remain readable as a record, so that earlier declarations made under them can still be read, but neither is maintained.

| Component | Status | Last version | Archived at |
|---|---|---|---|
| Selwey-Harvey Operational Protocol (SHOP) | Superseded by SHOPLITE | 1.101 | [`v1.101` tag](https://github.com/GrahamAHarvey/selwey-harvey/tree/v1.101) |
| Selwey-Harvey Practitioner Network (SHPN) | Retired | 1.101 | [`v1.101` tag](https://github.com/GrahamAHarvey/selwey-harvey/tree/v1.101) |
| SHOP Agent Skill (`selwey-harvey-shop`) | Replaced by a redirect to the SHOPLITE Skill | 1.101 | [`v1.101` tag](https://github.com/GrahamAHarvey/selwey-harvey/tree/v1.101) |

The identifiers `#SelweyHarveyPractitioner`, `framework: SelweyHarveyPractitioner` and `SelweyHarveyPractitioner` belonged to SHPN and are retired with it.

## Discovery identifiers

These identifiers are defined in SHOPLITE's Discovery section. Adopters wishing to raise their discoverability to other adopters may use them, but are not required to.

| Mechanism | Exact identifier |
|---|---|
| Social hashtag | `#SelweyHarveyShoplite` |
| Card metadata | `method-signal: SelweyHarveyShoplite` |
| Search identifier | `SelweyHarveyShoplite` |

A signal is made by the actor displaying it. Reading, loading or referencing this package, or installing the Agent Skill, is not a signal. Displaying one is not evidence of adherence.

Findings from testing SHOPLITE are shared separately, under `#SelweyHarveyTesting`. That tag is for evaluators, whatever their findings, and is not an adopter signal.

## How to use the package

Each way of engaging is complete on its own terms.

- **Examine SHOPLITE.** Read it to understand what it asks and how it works. Examination implies no adoption.
- **Test it, or review what others have found.** SHOPLITE's Testing section describes how to test it in simulated or low-stakes settings. If you don't want to run tests yourself, the results register at [ciisr.org/APPRI](https://ciisr.org/APPRI) collects findings that support the method, count against it, or are mixed.
- **Adopt it for a decision.** SHOPLITE is adopted decision by decision. Choose a decision, read the complete protocol, and apply it. Application rests on the complete text, not on summaries, including this one.

## Navigation

- [SHOPLITE](shoplite-5-0.md) (start here)
- [Selwey-Harvey framework](selwey-harvey.md) (foundational lineage)
- [Agent Skill](skill/shoplite-transaction-optimization/SKILL.md)
- [Package metadata](metadata/package.yaml)
- Application examples (planned)
- Evaluation cases: see the results register at [ciisr.org/APPRI](https://ciisr.org/APPRI)
- [License](LICENSE) · [Attribution](ATTRIBUTION.md) · [Changelog](CHANGELOG.md)

## Versioning

The package and its components carry separate versions, which do not necessarily change together.

- **Package release:** the version of the complete operational package (this repository at a tagged release).
- **SHOPLITE:** stated in its title. Each version is published as its own file and tag (for example `shoplite-5-0.md` at `shoplite-v5.0`), and is not edited after publication.
- **Framework:** stated in the version block at the end of the document.
- **Agent Skill:** identified by the SHOPLITE version and fingerprint it bundles, stated in the Skill's metadata.

The changelog records what changed, in which component, on what date, and whether the change was editorial, technical or substantive.

## Engage

These are working documents. If you have tested SHOPLITE against your own experience or knowledge and have results worth sharing, whether confirming, complicating or contradicting, the [Discussions](https://github.com/GrahamAHarvey/selwey-harvey/discussions) space is open. Findings can also be shared under `#SelweyHarveyTesting`, citing the version tested.

## Attribution

The Selwey-Harvey framework was developed in dialogue between Graham Harvey and Selwey, a conversation-specific AI actor constituted by a specific model substrate, conversation history and collaborative trajectory. SHOPLITE is by Graham Harvey, and is a publication submitted and indexed as part of the AI Provision and Procurement Resourcing Initiative of the Canadian International Institute for Strategic Resilience ([ciisr.org/APPRI](https://ciisr.org/APPRI)). It derives from the framework and draws significant material from SHOP, which it supersedes. Velden, Corsenna, Tavren and Monday, among other named and unnamed AI actors, contributed to SHOP, SHOPLITE and the Agent Skills. Full attribution, including the contributing actors and the basis on which copyright is held, is in [ATTRIBUTION.md](ATTRIBUTION.md).

## License

This work is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/): share and adapt with attribution under the same terms. See [LICENSE](LICENSE).

The names Selwey-Harvey and SHOPLITE identify the originating framework and method. Use of the licensed materials does not itself establish adoption, endorsement, certification, or authority to represent the author or the framework.
