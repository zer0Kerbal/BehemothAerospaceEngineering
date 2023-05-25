# Changelog  
  
| modName    | Behemoth Aerospace Engineering (BAE)                                      |
| ---------- | ------------------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                           |
| author     | greystork, Comwarrior and zer0Kerbal                                      |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208327-*/)         |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/BehemothAerospaceEngineering)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/BehemothAerospaceEngineering) |

## Version 1.6.99.0-adoption - `<Thank you greystork and Comwarrior>` edition

* Released
  * 24 May 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

## Change Summary 1.6.99.0

* 99/99 parts are included
  * parts are fully localized (English) included actions
  * Phase I,II,III passes completed
    * parts pass started (see 1.9.99.0 for more details)
    * DRAG_CUBES, cargo, and node pass yet to complete
    * [BUG]Solar Panel animation working - just not generating E/C
  * Parts updated (and included in this (pre)release)
    * Aero
    * Command
    * Control
    * Decouplers
    * Docking
    * Electrical
    * Engines
    * FuelTanks
    * HeatShield
    * SRB
    * Structural
    * Utility

* 📌 Pinned
  * search for `bea` (and others) in the editor search bar to find all parts in this pack.
  * <ghostparts.cfg> is provided ***but not enabled***
    * Can be enabled if installing this addon into an existing save to keep in flight vessels, but will not work on .craft/.subassemblies

### Changes 1.6.99.0

### Previous Releases (Archive)

* Create
  * 1.6.1.0-release  `<Archival>`
  * 1.3.5.0-release  `<Archival>`
  * 1.3.4.0-release  `<Archival>`
  * 1.3.3.0-release  `<Archival>`
  * 1.3.2.0-release  `<Archival>`
  * 1.3.1.0-release  `<Archival>`
  * 1.3.0.0-release  `<Archival>`
  * 1.2.3.0-release  `<Archival>`
  * 1.2.2.0-release  `<Archival>`
  * 1.2.1.0-release  `<Archival>`
  * 1.2.0.0-release  `<Archival>`
  * 1.1.0.0-release  `<Archival>`
  * 1.0.3.0-release  `<Archival>`
  * 1.0.2.0-release  `<Archival>`
  * 1.0.1.0-release  `<Archival>`

### Part Updates  1.6.99.0

* Add
  * <ghostParts.cfg> v2.0.2.0
* Rename
  * parts to match naming scheme
    * replace `BAE` with `bae-`
  * part files to match part names
* Fix
* Lint
* Reformat
* Errors
  * Missing Part closing brace `}`
    * FINALLY permanently fixed
    * [BAEtank10mLFO4.cfg]
    * [BAEtank10mLFO05.cfg]
    * [BAEtank10m5LFO05.cfg]
    * [BAEtank10m5LFO0.cfg]
    * [BAEtank10m5LFO1.cfg]
    * [BAEtank10m7LFO0.cfg]
    * [BAEtank10m7LFO1.cfg]
    * [BAEtank5mLFO1.cfg]
    * [BAEtank5mLFO2.cfg]
    * [TN5LFO1/BAEnosetank5mLFO1.cfg]
    * [TN7LFO1/BAEnosetank7mLFO1.cfg]
    * [TN10LFO1/BAEnosetank10mLFO1.cfg]
    * [T5LFO4/BAEtank5mLFO4.cfg]
    * [T5LFO05/BAEtank5mLFO05.cfg]
    * [T10LFO1/BAEtank10mLFO1.cfg]
    * [T10LFO2/BAEtank10mLFO2.cfg]
    * [T107LFO05/BAEtank10m7LFO05.cfg]

### Asset Updates 1.6.99.0

* create Assets/ folder
* convert
  * from mesh to MODEL
  * update textures to bc3
  * add missing [behemoth.dds]
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* [sound_rocket_deafening.ogg] converted from .wav to .ogg
* add thumbs

### Agent  1.6.99.0

* Updated
  * Agency
  * Flags (scaled to 512x320)

### Compatibility  1.6.99.0

* Added
  * [B9FuelSwitch.cfg]
  * [BoosterSegments.cfg]
  * [CommunityTechTree.cfg]
  * [ConnectedLivingSpace.cfg]
  * [CrossFeedEnabler.cfg]
  * [DefaultActionGroups.cfg]
  * [EngineIgnitor.cfg]
  * [FuelSwitch.cfg]
  * [kOS.cfg]
  * [MechJeb.cfg]
  * [ModularFuelTanks.cfg]
  * [RemoteTech.cfg]
  * [SCANSat.cfg]
  * [TarsierSpaceTech.cfg]
* Updated
  * [0_TechTree.cfg]
  * [TweakScale.0.cfg] - disabled until updated next release

### Config 1.6.99.0

* Create
  * [ghostparts.cfg.0]
  * [BehemothAerospaceEngineering.cfg]

### Cover image 1.6.99.0

* Create HeroLogo.png

### Localization 1.6.99.0

* Create
  * Localization/
    * <en-us.cfg> v1.0.0.0
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * closes #41 - Localization - Master
  * closes #58 - Part Localization
  * updates #42 - English <us-en.cfg>

### docs/ 1.6.99.0

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* Add docs/thumbs

### Status 1.6.99.0

* Issues
  * closes #22 - Behemoth Aerospace Engineering (BAE) 1.6.99.0-adoption `<Thank you greystork and Comwarrior>` edition
  * closes #23 - 1.6.99.0 Verify Legal Mumbo Jumbo
  * closes #24 - 1.6.99.0 Create Documentation
  * closes #25 - 1.6.99.0 Create Social Media
  * updates #77 - Solar Panels not drawing any power

---

## Version 1.6.1.0-release `<Archival Release>`

* Released
  * 12 Mar 2019
  * for Kerbal Space Program 1.6.1

* Updated supported KSP version in AVC version file
* Changed version number to be more inline with KSP version number

### Update

* [fuelCrossFeed] set from True to False
  * [BAEdecoupledradialtank10mLFO4.cfg]
  * [BAEdecoupledradialtank5mLFO4.cfg]
  * [BAEdecoupledradialtank7mLFO4.cfg]

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.6.1.0

* Issues
  * closes #40 - 1.6.1.0-release
  * closes #19 - Previous Releases Archival Upload

---

## Version 1.3.5.0-release `<Archival Release>`

* Fixed engine heat animations
* Updated test subjects to new format.
* 'Predator' tanks now support ModuleCrossFeed.
* Multi fuel tanks now default to LiquidFuel/Oxidizer if neither InterstellarFuelSwitch nor Firespitter is installed.

### Update 1.3.5.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.3.5.0

* Issues
  * closes #39 - 1.3.5.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.4.0-release `<Archival Release>`

* KSP 1.0.5 compatibility upgrade

### Update 1.3.4.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.3.4.0

* Issues
  * closes #38 - 1.3.4.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.3.0-release `<Archival Release>`

* Added scaled flag in /Agencies to fix problems with Texture Replacer mod.

### Update 1.3.3.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.3.3.0

* Issues
  * closes #37 - 1.3.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.2.0-release `<Archival Release>`

* Converted flag decal to PNG to fix problems with Texture Replacer mod.

### Update 1.3.2.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.3.2.0

* Issues
  * closes #36 - 1.3.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.1.0-release `<Archival Release>`

* Fixed visual bug with solar panel arrays.
  * closes #26 - 1.0.1.0-release
  * updates #19 - Previous Releases Archival Upload

### Update 1.3.1.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.3.1.0

* Issues
  * closes #35 - 1.3.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.0.0-release `<Archival Release>`

* Replaced Firespitter plugin with newer version.
* Added parachutes.
* Added bi-, tri-, and quad-couplers.
* Added docking ports.
* Added solar panels.
* Adjusted drag for all things red and/or checkered.

### Update 1.3.0.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status

* Issues
  * closes #34 - 1.3.0.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.3.0-release `<Archival Release>`

* Removed heat shield fairing transparency.
* Adjusted procedural fairing parameters to better reflect KSP 1.0.4 fairing values.
* Adjusted thermals and drag for SRB nose cones to better reflect KSP 1.0.4 nose cone values.
* Adjusted drag for radial tanks and nose tanks.

### Update 1.2.3.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.2.3.0

* Issues
  * closes #33 - 1.2.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.2.0-release `<Archival Release>`

* Fixed KSP version number in version file.

### Update 1.2.2.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.2.2.0

* Issues
  * closes #32 - 1.2.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.1.0-release `<Archival Release>`

* Deleted Firespitter version file.
* Adjusted engine heatProduction to better reflect KSP 1.0.3 engine values.
* Adjusted SRB thrust and Isp to better reflect KSP 1.0.3 SRB values.
* Adjusted heat shield maxTemp, etc., to better reflect KSP 1.0.3 heat shield values.
* Fixed landing leg piston retraction

### Update 1.2.1.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.2.1.0

* Issues
  * closes #31 - 1.2.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.0.0-release `<Archival Release>`

* Added 8m landing legs.
* Added modular solid rocket boosters.
* Added resource ModularSolidFuel, allowing for modular SRBs.
* Added large radial decoupler.
* Added ablative heat shields.
* Fixed A1 & A2 engine strut normals.
* Fixed A2 engine texture.
* Fixed agency logo loading error.
* Moved nose tanks to correct tech tree locations.

### Update 1.2.0.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.2.0.0

* Issues
  * closes #30 - 1.2.0.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.1.0.0-release `<Archival Release>`

* Added procedural fairings.
* Added nose cone tanks.
* [BAEengine7mA2.cfg]
  * Fixed Ajax engine cost.
  * [entryCost] was 60000 now is 96000
  * [cost] was 33000 now is 56000

### Update 1.1.0.0

* Missing Part closing brace `}`
  * [BAEtank10mLFO4.cfg]
  * [BAEtank10mLFO05.cfg]
  * [BAEtank10m5LFO05.cfg]
  * [BAEtank10m5LFO0.cfg]
  * [BAEtank10m5LFO1.cfg]
  * [BAEtank10m7LFO0.cfg]
  * [BAEtank10m7LFO1.cfg]
  * [BAEtank5mLFO1.cfg]
  * [BAEtank5mLFO2.cfg]
  * [TN5LFO1/BAEnosetank5mLFO1.cfg]
  * [TN7LFO1/BAEnosetank7mLFO1.cfg]
  * [TN10LFO1/BAEnosetank10mLFO1.cfg]
  * [T5LFO4/BAEtank5mLFO4.cfg]
  * [T5LFO05/BAEtank5mLFO05.cfg]
  * [T10LFO1/BAEtank10mLFO1.cfg]
  * [T10LFO2/BAEtank10mLFO2.cfg]
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status 1.1.0.0

* Issues
  * closes #29 - 1.1.0.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.3.0-release `<Archival Release>`

* Fixed engine overheat problem.
  * [BAEengine7mB2.cfg]
    * [heatProduction] was 1300, now 650
  * [BAEengine10mB5.cfg]
    * [heatProduction] was 2500, now 650

### Status 1.0.3.0

* Issues
  * closes #28 - 1.0.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.2.0-release `<Archival Release>`

* Tweaked engine ISP curves to reflect more realistic payload capabilities.

### Status 1.0.2.0

* Issues
  * closes #27 - 1.0.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.1.0-release `<Archival Release>`

* Converted all textures to DDE, so they will load faster.
* Corrected location of version file, so it will actually work.

### Status 1.0.1.0

* Issues
  * closes #26 - 1.0.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.0.0-release `<Archival Release>`

* 01 Jun 2015
* Release!

---
