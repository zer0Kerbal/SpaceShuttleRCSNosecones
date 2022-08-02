---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Space Shuttle RCS Nosecone (SSRN)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Space Shuttle RCS Nosecone (SSRN)

[Home](./index.md)

Ever thought, that you need an actual nosecone for plane parts? This parts addon adds nosecones containing Monopropellant and mostly translational RCS-Thrusters. Ideal for keeping your nose up during reentry! For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `SpaceShuttleRCSNosecone` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/SpaceShuttleRCSNosecone`
* Extract the package's `SpaceShuttleRCSNosecone/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/SpaceShuttleRCSNosecone` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/SpaceShuttleRCSNosecone`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/SpaceShuttleRCSNosecone`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/SpaceShuttleRCSNosecone`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [SpaceShuttleRCSNosecone]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * GPL-3.0.txt
        ManualInstallation.htm
      * readme.htm
      * SpaceShuttleRCSNosecone.version
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
