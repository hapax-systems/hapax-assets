# hapax-assets Agent Instructions

This repository is published by **Hapax Research Lab** under the `hapax-systems` GitHub organization. Do not create, move, or point repository automation outside `hapax-systems`.

## Review Guidelines

External GitHub App reviewers are advisory unless a governed task explicitly routes them into the review process.

- Preserve the `all-green` aggregate check in `.github/workflows/ci.yml` for branch ruleset compliance.
- Never print or persist plaintext secrets; use the deployment secret store or GitHub Secrets.
- Validate `_manifest.yaml`, committed asset hashes, `index.html`, and provenance files (`python3 scripts/validate_manifest.py`) before opening or merging a pull request.
- Keep Pages URLs under `https://hapax-systems.github.io/hapax-assets/`.
