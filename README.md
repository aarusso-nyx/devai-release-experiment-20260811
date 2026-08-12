# DEVAI disposable release experiments

This temporary repository isolates Pages-mode and GitHub Packages
delete/republication experiments from the DEVAI product repository.

The measured outcomes are recorded in `evidence/experiments-20260812.json`. They confirm that an
Actions Pages deployment requires workflow mode and that a deleted disposable GitHub Packages
version can be republished with the same version and bytes. DEVAI therefore treats the immutable
GitHub Release manifest and `SHA256SUMS`, not the package mirror, as the canonical stable identity.
