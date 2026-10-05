# Upstream provenance

This repository is a standalone copy of `packages/pi-goal` from [narumiruna/pi-extensions](https://github.com/narumiruna/pi-extensions) at commit `f5f197f9ada9054861168632ec372a7030a6f28d` (`@narumitw/pi-goal` 0.54.8), with its MIT license and authorship preserved. `scripts/runtime-builder.mjs` and `test/support.ts` came from the same upstream commit so the package can build and test independently.

Rodrigo's changes add the optional `pi:agent-job-wait:v1` bridge and tests. This GitHub repository is separate because the pre-existing `rodrigojager/pi-extensions` fork tracks a different upstream tree and does not contain `packages/pi-goal`.
