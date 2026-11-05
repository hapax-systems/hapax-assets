<!-- hapax-sdlc:preamble:begin -->

# hapax-assets

`hapax-assets` is the static brand and publication asset mirror for **Hapax Research Lab** ([hapaxresearch.com](https://hapaxresearch.com)).

## Reader promise

Public GitHub Pages mirror ([hapax-systems.github.io/hapax-assets/](https://hapax-systems.github.io/hapax-assets/)) serving reviewed publication and aesthetic artifacts with explicit provenance and per-asset license notices.

## Reader value

Provides stable, SHA-verified asset URLs and auditable attribution records (`_manifest.yaml`, `_NOTICES.md`) for Hapax Research Lab web and publication surfaces.

## Claim ceiling

Static delivery mirror only; asset selection and approval occur upstream before publication here.

## License and rights

- **Documentation & metadata:** Creative Commons Attribution 4.0 International (`CC-BY-4.0`); see [LICENSE](LICENSE) and [LICENSE-SCOPE.md](LICENSE-SCOPE.md).
- **Trademark & brand-mark reservation:** All trademarks, wordmarks, monograms, and brand marks of **Hapax Research Lab** (`Hapax Research LLC`) are expressly reserved and are not licensed under `CC-BY-4.0`.
- **Mirrored third-party assets:** Governed by their respective upstream licenses (`BSD-3-Clause`, `CC-BY-SA-4.0`, `CC0-1.0`) recorded in [`_manifest.yaml`](_manifest.yaml) and [`_NOTICES.md`](_NOTICES.md).

## Public boundary

- Issues are redirect-only; no discussions and no unsolicited pull requests are accepted; see [CONTRIBUTING.md](CONTRIBUTING.md) and [SUPPORT.md](SUPPORT.md).
- Security disclosures and factual correction proposals: [hrl-han@hapaxresearch.com](mailto:hrl-han@hapaxresearch.com) (see [SECURITY.md](SECURITY.md) and [hapaxresearch.com/about/#contact](https://hapaxresearch.com/about/#contact)).
- Governance reference: [hapax-constitution](https://github.com/hapax-systems/hapax-constitution).

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
