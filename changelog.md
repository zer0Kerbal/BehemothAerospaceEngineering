# Changelog  
  
| modName    | Behemoth Aerospace Engineering (BAE)                                      |
| ---------- | ------------------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                           |
| author     | greystork, Comwarrior and zer0Kerbal                                      |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208327-*/)         |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/BehemothAerospaceEngineering)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/BehemothAerospaceEngineering) |
| spacedock  | (https://spacedock.info/mod/225)                                          |
| ckan       | BehemothAerospaceEngineering                                              |

## Version 1.6.99.0-adoption `<Purple Rhino>` edition

### docs/

* Update
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
* Add
  * [404.md] v1.0.3.1
  * [Disclaimer.md] v1.0.0.0
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [PartInvoice.md] v1.1.3.1
  * [_config.yml]* closes #20 - docs/

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
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
* add thumbs

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.1.0
    * [quickstart.md] v1.0.1.0
  * closes #41 - Localization - Master
  * closes #42 - English <us-en.cfg>
  * closes #58 - Part Localization

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
  * [[T107LFO05/BAEtank10m7LFO05.cfg]

### Status

* Issues
  * closes #22 - Behemoth Aerospace Engineering (BAE) 1.6.99.0-adoption `<NAME>` edition
  * closes #23 - 1.6.99.0 Verify Legal Mumbo Jumbo
  * closes #24 - 1.6.99.0 Create Documentation
  * closes #25 - 1.6.99.0 Create Social Media
* Housekeeping
  * closes #3 - ### Documentation
  * closes #4 - ### Github
  * closes #5 - ### Adoption
  * closes #6 - ### Social
  * closes #7 - ### Repo
  * closes #8 - Localization
  * closes #9 - ### Social
  * closes #10 - ### Release
  * closes #11 - BehemothAerospaceEngineering (BAE) Version 1.6.99.0-adoption `<EDITION>` edition
  * closes #12 - ### Legal MumboJumbo
  * closes #13 - ### Update documentation
  * closes #14 - Localization - en-us.cfg (English)
  * closes #15 - Localization - pt-br.cfg Brazil
  * closes #16 - Localization - zh-cn.cfg - Simplified Chinese
  * closes #17 - 1.6.99.0-adoption early release
  * closes #18 - GitHub repo update

---

## Version 1.6.1.0-release

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

### Status

* Issues
  * closes #40 - 1.6.1.0-release
  * closes #19 - Previous Releases Archival Upload

---

## Version 1.3.5.0-release

* Fixed engine heat animations
* Updated test subjects to new format.
* 'Predator' tanks now support ModuleCrossFeed.
* Multi fuel tanks now default to LiquidFuel/Oxidizer if neither InterstellarFuelSwitch nor Firespitter is installed.

### Update

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
  * closes #39 - 1.3.5.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.4.0-release

* KSP 1.0.5 compatibility upgrade

### Update

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
  * closes #38 - 1.3.4.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.3.0-release

* Added scaled flag in /Agencies to fix problems with Texture Replacer mod.

### Update

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
  * closes #37 - 1.3.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.2.0-release

* Converted flag decal to PNG to fix problems with Texture Replacer mod.

### Update

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
  * closes #36 - 1.3.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.1.0-release

* Fixed visual bug with solar panel arrays.
  * closes #26 - 1.0.1.0-release
  * updates #19 - Previous Releases Archival Upload

### Update

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
  * closes #35 - 1.3.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.3.0.0-release

* Replaced Firespitter plugin with newer version.
* Added parachutes.
* Added bi-, tri-, and quad-couplers.
* Added docking ports.
* Added solar panels.
* Adjusted drag for all things red and/or checkered.

### Update

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

## Version 1.2.3.0-release

* Removed heat shield fairing transparency.
* Adjusted procedural fairing parameters to better reflect KSP 1.0.4 fairing values.
* Adjusted thermals and drag for SRB nose cones to better reflect KSP 1.0.4 nose cone values.
* Adjusted drag for radial tanks and nose tanks.

### Update

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
  * closes #33 - 1.2.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.2.0-release

* Fixed KSP version number in version file.

### Update

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
  * closes #32 - 1.2.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.1.0-release

* Deleted Firespitter version file.
* Adjusted engine heatProduction to better reflect KSP 1.0.3 engine values.
* Adjusted SRB thrust and Isp to better reflect KSP 1.0.3 SRB values.
* Adjusted heat shield maxTemp, etc., to better reflect KSP 1.0.3 heat shield values.
* Fixed landing leg piston retraction

### Update

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
  * closes #31 - 1.2.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.2.0.0-release

* Added 8m landing legs.
* Added modular solid rocket boosters.
* Added resource ModularSolidFuel, allowing for modular SRBs.
* Added large radial decoupler.
* Added ablative heat shields.
* Fixed A1 & A2 engine strut normals.
* Fixed A2 engine texture.
* Fixed agency logo loading error.
* Moved nose tanks to correct tech tree locations.

### Update

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
  * closes #30 - 1.2.0.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.1.0.0-release

* Added procedural fairings.
* Added nose cone tanks.
* [BAEengine7mA2.cfg]
  * Fixed Ajax engine cost.
  * [entryCost] was 60000 now is 96000
  * [cost] was 33000 now is 56000

### Update

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
  * closes #29 - 1.1.0.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.3.0-release

* Fixed engine overheat problem.
  * [BAEengine7mB2.cfg]
    * [heatProduction] was 1300, now 650
  * [BAEengine10mB5.cfg]
    * [heatProduction] was 2500, now 650

### Status

* Issues
  * closes #28 - 1.0.3.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.2.0-release

* Tweaked engine ISP curves to reflect more realistic payload capabilities.

### Status

* Issues
  * closes #27 - 1.0.2.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.1.0-release

* Converted all textures to DDE, so they will load faster.
* Corrected location of version file, so it will actually work.

### Status

* Issues
  * closes #26 - 1.0.1.0-release
  * updates #19 - Previous Releases Archival Upload

---

## Version 1.0.0.0-release

* Release!

---
