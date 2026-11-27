# Contributing

phoskintime-core is part of the PhosKinTime family: phoskintime-sim (model + simulation),
phoskintime-core (fitting), phoskintime-vis (visualisation). This repository does fitting and imports the model from phoskintime-sim; it never defines its own copy.

- Work on a branch; `main` only changes through squash-merged pull requests.
- Scientific changes (equations, solvers, tolerances, parameter/state order, units, seeds)
  need owner review, the `scientific` label and a before/after comparison.
- Contract changes (bundle schema, sim API, model-version ID) are versioned; label `contract`.
- Release tags `v*` are immutable.
