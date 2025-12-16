# Dendritic Nix flakes examples

This repo serves as example implementation of the [Dendritic](https://github.com/mightyiam/dendritic) pattern
using different flake libraries/frameworks.

For non-flakes see [vic/dendritic-unflake](https://github.com/vic/dendritic-unflake)

## Motivation

The purpose of this repo is not to implement the exact same configuration in different frameworks.
Nor have a feature-wise comparission nor saying which library is best.

Instead, we are trying to provide Dendritic examples with existing libraries so that people can **choose**
whatever library/framework aligns better with their needs and way of thinking.

Each library/framework might have different features not shared by others, we will try to document them
only if they have a direct-impact on the Dendritic pattern.

## What is considered Dendritic

For the purpose of this repo, a framework is considered Dendritic if it allows:

- All top-level files are nix modules of the same `class`.
- Allows each top-level module to configure a **cross-cutting concern** over several Nix `class`es.
- Allows organizing top-level modules in a way that serves as a mind-map of usability concerns. 

Not necessarily required to be considered Dendritic.

- auto-import of all modules
- create nixosConfigurations or any other configuration.

## Nix Configuration Frameworks/Libs

- [flake-parts](https://flake.parts)
- [unify](https://codeberg.org/quasigod/unify/src/branch/main)
- [den](https://den.oeiuwq.com)
- [imp](https://imp-nix.github.io/)
- [nixy](https://github.com/anialic/nixy)

