---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Behemoth Aerospace Engineering (BAE)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Behemoth Aerospace Engineering (BAE)

[Home](./index.md)

This parts pack contains engines, tanks, and other part categories in three sizes that do not exist in stock KSP, namely 5m, 7.5m, and 10m. Parts are color-coded according to the universal electronic color code (http://en.wikipedia.org/wiki/Electronic_color_code), simply because the author is an old RDAF radar technician. Hence, size4 (5m) is yellow, size5 (7.5m) is green, and size6 (10m) is blue.

Engines are kept at reasonable thrust figures and are thus not overpowered compared to the thrust/size curve of stock parts. The same goes for reaction wheels. Big spaceships are going to be sluggish, as one would expect.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the BehemothAerospaceEngineering folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/BehemothAerospaceEngineering`
* Extract the package's `BehemothAerospaceEngineering/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/BehemothAerospaceEngineering` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/BehemothAerospaceEngineering`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/BehemothAerospaceEngineering`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/BehemothAerospaceEngineering`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [BehemothAerospaceEngineering]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [PartList]
        ...
      + [Parts]
        ...
      + [Resources]
        ...
      + [Sounds]
        ...
      * #.#.#.#.htm
      * changelog.md
      * CC-BY-NC-SA-4.0.txt
      * readme.htm
      * BehemothAerospaceEngineering.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
