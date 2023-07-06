---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.1.0
Mkerb Inc (MKERB)
created: 23 Mar 2023
updated: 05 Jul 2023

<!-- based upon work by Lisias -->

## [Mkerb Inc (MKERB)][mod]

[Home](./index.md)

Agent, flags and common configs for Mkerb Inc.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `Mkerb` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Mkerb/MkerbLtd`
* Extract the package's `Mkerb` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Mkerb` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Mkerb/MkerbLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Mkerb/MkerbLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/Mkerb/MkerbLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Mkerb]
      + [MkerbLtd]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * GP:2-0.txt
        * MkerbLtd.version
        * ManualInstallation.htm
        * readme.htm
        ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/MkerbInc "Mkerb Inc (MKERB)"