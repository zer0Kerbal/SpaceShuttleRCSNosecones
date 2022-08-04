---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
# layout: bare
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- 
hdr-changelog.md v1.0.0.0
SpaceShuttleRCSNosecone
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Space Shuttle RCS Nosecones (RCSN) (SSCN)                             |
| ---------- | --------------------------------------------------------------------- |
| license    | GPL-3.0                                                               |
| author     | Kamik and zer0Kerbal                                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209188-*/)     |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SpaceShuttleRCSNosecones)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SpaceShuttleRCSNosecones) |
| spacedock  | (https://spacedock.info/mod/3068)                                     |
| ckan       | SpaceShuttleRCSNosecones                                              |

## Version 3.0.99.0-adoption - `<Cone Anyone?>` edition

* 01 Aug 2022
* Released for Kerbal Space Program 1.12.x

### Adoption by zer0Kerbal

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* convert from mbm to png
  * HRuv2.mbm (3 mb) --> HRuv2.png (84.5 kb)
  * UV23.mbm (3 mb) --> UV23.png (91.2 kb)
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
* closes #28 - Asset Updates

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * Optional
  * [PartsCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* Update
  * [.version]
    * remove [KSP_VERSION_MAX]
* closes #27 - docs/

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #7 - Localization Master
* closes #8 - English <en-us.cfg>
* closes #25 - Part Localization
* closes #29 - Localization config

### Parts

* Add
  * header
  * [skinMaxTemp] = 2700
  * [emissiveConstant] = 0.9
  * [thermalMassModifier] = 6.0
  * [DRAG_CUBE]
  * [tags] = #autoLOC_500941 //#autoLOC_500941 = cluster control dock maneuver manoeuvre react rendezvous rotate stab steer translate
* Update
  * [category] to Control from Utility
  * [bulkheadProfiles] = mk3, srf
  * [entryCost] from 6000 to 8000
  * [cost] from 100 to 1000
  * [maximum_drag] from 0.2 to 0.1
  * [minimum_drag] from 0.2 to 0.1
  * [angularDrag] from 1 to 0.5
  * [maxTemp] from 3200 to 1500
  * [attachRules] 1,1,1,1,1 to 1,1,1,1,0
  * [EFFECTS]
    * [running]
      * [MODEL_MULTI_PARTICLE]
        * [transformName] = rcsT
      * [AUDIO_MULTI_POOL]
        * [transformName] = rcsT
* closes #32 - Update Parts
* closes #33 - [BUG] Missing FX on running

|                 | rcsn-short | rcsn-long |
| :-------------- | :--------: | :-------: |
| entryCost       |    8000    |   9000    |
| cost            |    1000    |   1250    |
| mass            |     1      |   1.05    |
| MonoPropellant  |    200     |    225    |
| thrusterPower   |     1      |   1.25    |
| ModuleCargoPart |    1050    |   1500    |

### Add localized tags to parts

* Add
  * [SpaceShuttleRCSNosecone.cfg] v1.0.0.0
    * adds
      * localized tags to parts
      * [tags] = #autoLOC_500111 //#autoLOC_500111 = aero aircraft booster )cap drag fligh plane rocket speed stab stream
* closes #30 - Add localized tags to parts

### Status

1 - Space Shuttle RCS Nosecones (RCSN) (SSNC) 3.0.99.0-adoption `<Cone Anyone?>` edition
2 - 3.0.99.0 Create Legal Mumbo Jumbo
3 - 3.0.99.0 Create Documentation
4 - 3.0.99.0 Create Social Media

---

## Version 3.0.0.0-release - <Thank you Kamik423> edition

* 29 Dec 2014
* Released for Kerbal Space Program 0.90

* Better Texture
* Fixed thrusters not being symmetrical
* Fixed not showing up in Career mode (Specialized Control)

* Add
  * [ghostParts.cfg] v1.3.0.0
    * ssrn-long --> ssncLong
    * ssrn-short --> ssncShort
    * to provide continuity with future versions

### Status 3.0.0.0

* Issues
  * closes #6 - Previous Release - Archival

---

## Version 2.0.0.0-release

* Added a new nosecone that has fits with the MK3 Cockpit
* Bugfixes

---

## Version 1.0.0.0-release

* Initial release
* Added first nosecone

---
