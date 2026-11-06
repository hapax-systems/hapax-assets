<!-- hapax-sdlc:preamble:begin -->
<!-- hapax-public:surface=github.repo.hapax-assets.readme.preamble:begin -->

# hapax-assets

`hapax-assets` is a public asset mirror for the **Hapax Research Lab** portfolio ([hapaxresearch.com](https://hapaxresearch.com)). Source of truth and approval remain outside this mirror.

## Reader promise

Public GitHub Pages mirror serving reviewed publication and aesthetic artifacts with SHA-256 manifest verification and per-asset license notices.

## Reader value

Provides stable, checksum-verified asset URLs and auditable attribution records (_manifest.yaml, _NOTICES.md) for Hapax Research Lab web and publication surfaces.

## Claim ceiling

Static delivery mirror only; asset selection and approval occur upstream before publication here, and licenses remain per-asset.

## License and rights

Original documentation, index.html, and repository metadata use CC-BY-4.0 (see LICENSE and LICENSE-SCOPE.md); trademarks and brand marks of Hapax Research Lab (Hapax Research LLC) are expressly reserved; mirrored third-party assets retain their declared upstream licenses (BSD-3-Clause, CC-BY-SA-4.0, CC0-1.0) in _manifest.yaml and _NOTICES.md, so licenses remain per-asset.

Rendered summary: CC BY 4.0 for original documentation and metadata (trademarks reserved; mirrored third-party assets retain declared upstream licenses). See `LICENSE-SCOPE.md`, `NOTICE.md`, `_NOTICES.md`, `_manifest.yaml`, `CITATION.cff`, and `.zenodo.json` for the authority surfaces.

## Public boundary

- Issues are redirect-only; no discussions, no pull requests accepted; see `CONTRIBUTING.md` and `SUPPORT.md`
- Published by **Hapax Research Lab** (`hrl-han`, [hapaxresearch.com](https://hapaxresearch.com)). Legal entity (as filed): Hapax Research LLC, organized in Wyoming on 2026-05-10, filing ID 2026-001973400.
- Security disclosures and factual correction proposals: `hrl-han@hapaxresearch.com` (see `SECURITY.md` and [hapaxresearch.com/about/#contact](https://hapaxresearch.com/about/#contact)). The network commits to receipt, retention and published correction. It promises no response time.
- Public copy uses `hapax-systems` organization links for first-party repositories; README text is orientation rather than a live runtime receipt.
- Governance reference: https://github.com/hapax-systems/hapax-constitution

## Portfolio position

Public GitHub Pages mirror (https://hapax-systems.github.io/hapax-assets/) serving checksum-verified visual, font, and publication assets for Hapax Research Lab web surfaces.

<!-- hapax-public:surface=github.repo.hapax-assets.readme.preamble:end -->
<!-- hapax-sdlc:preamble:end -->

## Overview

`hapax-assets` hosts immutable, checksum-verified assets published for **Hapax Research Lab** web properties ([hapaxresearch.com](https://hapaxresearch.com), [hapax.weblog.lol](https://hapax.weblog.lol), and [hapax.omg.lol](https://hapax.omg.lol)) via [GitHub Pages](https://hapax-systems.github.io/hapax-assets/).

| Surface | Role |
|---|---|
| [GitHub Pages index](https://hapax-systems.github.io/hapax-assets/) | Static landing page (`index.html`) and CORS-enabled asset origin. |
| [`_manifest.yaml`](_manifest.yaml) | Machine-validated SHA-256 inventory, source URLs, and per-asset license identifiers. |
| [`_NOTICES.md`](_NOTICES.md) | Third-party attribution notices (`BSD-3-Clause`, `CC-BY-SA-4.0`, `CC0-1.0`). |
| [`LICENSE`](LICENSE) & [`LICENSE-SCOPE.md`](LICENSE-SCOPE.md) | `CC-BY-4.0` grant for original documentation/metadata plus explicit trademark/brand-mark reservation. |

## Verification

Validate all manifest checksums and provenance files locally:

```sh
python3 scripts/validate_manifest.py
```

## License & Trademark Reservation

Original documentation and repository metadata are available under **CC-BY-4.0** ([LICENSE](LICENSE)). Trademarks, logos, and brand marks of **Hapax Research Lab** (`Hapax Research LLC`) are expressly reserved and excluded from the `CC-BY-4.0` grant. Mirrored third-party files remain under their upstream licenses documented in [`_NOTICES.md`](_NOTICES.md).

---

*HACA-C v0.3.15, the lab's draft rule for labelling machine-made text, not an external certification. No request to a natural person to approve the final wording, and no such approval, was found in hrl-han's sending, review and coordination records when the text was released. hrl-han releases a text once its checking is complete, under a standing rule that hrl-han's principal, who is not named in this text, adopted before the text was drafted. Review record: https://hapaxresearch.com/review-record/ (open to anyone). This label records how the text was made; it does not certify that the text is true. An unaltered record can contain false claims or miss relevant events.*
