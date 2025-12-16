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

## Examples

The following is the planned list of libs/frameworks that allow to implement the Dendritic pattern.
Feel free to send other implementations or candidate suggestions. Some will be removed it it is not
possible for configurations to be considered Dendritic.

- [flake-parts](https://flake.parts) [branch:TODO]
- [unify](https://codeberg.org/quasigod/unify/src/branch/main) [branch:TODO]
- [den](https://den.oeiuwq.com) [branch:TODO]
- [imp](https://imp-nix.github.io/imp.lib/) [branch:TODO]
- [nixy](https://github.com/anialic/nixy) [branch:TODO]
- [falake](https://codeberg.org/FrdrCkII/falake) [branch:TODO]
- [flakelight](https://github.com/nix-community/flakelight) [branch:TODO]


