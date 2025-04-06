ASET Consolidated Avionics Pack by Alexustas, adopted by Stone Blue

---------------------------------------------------------------------------------------------------------------------------------------------------

# Unreleased

- Changes:

  - add NEEDS clauses around configs that require FAR so they don't emit errors when FAR isn't installed

---------------------------------------------------------------------------------------------------------------------------------------------------

# v3.0.1 - 2023-04-13

- Changes:

  - Converted all pngs to dds
  - fix missing "/" preceding a comment in ASET_HSI.cfg
  - fix missing "/" preceding a comment in ASET_AIRCRAFT_ENGINE_TempGauge.cfg
  - fix missing "/" preceding a comment in ASET_AIRCRAFT_INT_TempGauge.cfg
  - fix missing "/" preceding a comment in ASET_AIRCRAFT_SKIN_TempGauge.cfg
  - fix copy/paste error, leaving incorrect, open PROP node & name in ASET_B-Knob_LD-CP_LEFT.cfg

---------------------------------------------------------------------------------------------------------------------------------------------------

# v3.0.0 - 2023-02-11

- Changes:

  - Removed unecessary/redundant .zips that have been included in previous release packages
  - Simplified/combined RPM_EngineReverser.cfg patch
  - Moved forum thread from WIP/Add-Development to Add-Releases
  - Released on SpaceDock & CKAN

---------------------------------------------------------------------------------------------------------------------------------------------------

# v2.9.0 - 2023-02-07

Initial adoption Release by Stone Blue
Since this is an initial adoption release, NO changes are made to the content, OTHER than those listed below.
Vers. 2.9.0 content is an *exact copy* of v2.1, other than noted below. All vers. 2.9.x changes will only contain repo and distribution changes to get the bugs worked out.
Once changes to actual mod content start, versioning will go to v3.0.x

- Changes:

  - Created new forum release thread: [ASET Consolidated- Avionics, Props, & IVA Pack](https://forum.kerbalspaceprogram.com/index.php?/topic/211905-1125-181-aset-consolidated-avionics-props-iva-packs/)
  - Created Github repo
  - Addition of .version file
  - Updated/formatted CHANGELOG & README
  - Relevant documentation added to repo
  - Added Extras folder, initially contains map of Earth, by slaintemaith, to replace Kerbin map on some props, for use in RO/RP-1

---------------------------------------------------------------------------------------------------------------------------------------------------

*****  Below is original changelog from alexustas' last v2.1 release ****

---------------------------------------------------------------------------------------------------------------------------------------------------

# v2.1 - 26/11/2017

- Changes:

  - Optimization and various improvements
  - Fixed an error in Aero Charts thanks to lazr2222 and MOARdv.

---------------------------------------------------------------------------------------------------------------------------------------------------

# v2.0 - 09/02-2017

- Changes:

  - Almost all props were rebuilt due to the migration to Unity5, & to use new RPM features.
  - Most props now support the "COLOR_OVERRIDE" feature, which gives all IVA-makers ample opportunity to customize their own IVA.
  - The "ASET_B-Knob" props are now modular: you can combine the switch model, collider model & label using the MODEL{} node to create your own variations of this prop.
     Two to Six knob positions are supported.

- What’s new:

  - Added: Full set of analog Temperature indicators (gauges)
  - Added: Analog Brake Force indicators (gauges)
  - Added: Full set of analog Engine indicators (gauges):
    - Air Flow
    - Fuel Flow
    - Engine Mode (Primary/Secondary)
    - Throttle Limit
    - New design of the Throttle/Thrust Indicator
    - New design of the Vertical Speed Indicator
    - New design of the Heading Indicator
    - LCD-display for the Estimated Time of Flight & Distance
    - LCD-display for the GPS Coordinates
    - Toggle-switches for the Engine Reverse & Engine Mode controls, Fuel Cell & Emergency Power Generator Controls
    - A fully functional system of radio navigation, which includes:
      - Realistic RMI & HSI Indicators, which support NDB, VOR & ILS
      - Two NAV-radio Units
      - DME Unit
      - Network of nav facilities covering the surface of Kerbin
      - ILS complex for the KSC Airfield
      - Kerbin Aerocharts