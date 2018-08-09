# Mark IV Spaceplane System :: Change Log

* 2017-1027: 2.4.0 (ChrisAdderley) for KSP 1.3.1
	+ KSP 1.3.1
	+ Updated MM to 2.8.1
	+ Updated B9PartSwitch to 1.10.0
	+ Updated CRP to 0.8.0
	+ Updated MiniAVC to 1.0.3.3
	+ Converted all strings to KSP 1.3 localization methods
	+ Updated CryoTanks patch with new mass ratios: LH2 and LH2O tanks are 1.15x as heavy as their rocket variants (as with stock)
	+ Deprecated Firespitter Core in favour of KerbalActuators for all propeller-type engines:
		- Better handling of forward/reverse thrust for various turboprops
		- Better performance
* 2017-0310: 2.3.6 (ChrisAdderley) for KSP 1.2.2
	+ Fixed large cargo bay/drop bay counting its forward area as closed when opened as vice versa
	+ Fixed lift fans generating static lift at incorrect angles
	+ Reduced lift fans' static lift by 50%
	+ Increased the range and response speed of lift fan gimbals
* 2017-0302: 2.3.5 (ChrisAdderley) for KSP 1.2.2
	+ Fixed missing ModuleManager in the download
	+ Updated B9Partswitch to 1.7.1
	+ Updated CRP to 0.6.6
	+ Fix for crew hatch obscured problem on Mk4 Crew Cabin
	+ New drag cube for Mk4 Shoulder Intake
	+ Fix for cargo bay node occlusion (requires rebuild of your cargo bays!)
	+ Fix for large cargo bay's occlusion testing spheres
	+ Inverted animation directions for cargo bays; now open at start.
	+ Reduced air intake ratio of lift fans in LF mode (22 -> 14)
	+ Reduced all fuselage body lift values by 33%
	+ Fixed incorrect node for the AE-4 Turboramjet
	+ Fixed incorrect velocity curve for Arcadia-593 Turbofan thrust reverser
* 2017-0125: 2.3.4 (ChrisAdderley) for KSP 1.2.2
	+ Marked for KSP 1.2.2
	+ Updated CRP to 0.6.4
	+ Updated MM to 2.7.5
	+ Updated B9PartSwitch to 1.5.3
	+ Updated Firespitter to 7.5.1
	+ Updated DeployableEngines to 2.1.0
	+ Fixed node size issue in SCIMITAR cfg
	+ Some tweaks to Crew Cabin drag parameters
	+ Fixed a MM path throwing errors on startup
* 2016-1122: 2.3.3 (ChrisAdderley) for KSP 1.2.1
	+ Fixed problems with Heavy RCS Blister thrust vectors
	+ Fixed cargo bay module occluding the wrong nodes for all regular/ventral bays
	+ Added patch to add cryogenic LH2 and LH2/O fuel storage modes to certain parts (fuselages, tails and adapters) if CryoTanks is installed.
* 2016-1118: 2.3.2 (ChrisAdderley) for KSP 1.2.1
 	+ Marked for KSP 1.2.1
 	+ Updated CRP to 0.6.3
 	+ Updated MM to 2.7.4
 	+ Cabin lights are now tied to the Lights action group
 	+ Increased collection distance for EVA science for both cockpits
* 2016-1021: 2.3.0 (ChrisAdderley) for KSP 1.2
 	+ KSP 1.2
 	+ Dependency update
 	+ Electric drive fans now function below 0.1 atmospheres
 	+ Added 1.2 features to parts
 	+ Thunderhawk cockpit can now function as a control pointAll RCS blocks converted to ModuleRCSFX, adds sound and new FX
 	+ Fixed ARV-50-2 Heavy Symmetric RCS Blister not showing up in career
 	+ Fixed missing cross sectional profile for Mk4 Crew Cabin
 	+ Added missing part search tags to all parts
 	+ Fixed reverse thrust on turboprops
 	+ Corrected instances of inconsistent manufacturer names
 	+ Fixed some typos in some part descriptions
 	+ Moved all cargo bay parts to the Payload category
 	+ Moved all docking parts to the Coupling category
 	+ Reexported all engine FX with correct layering to fix interaction with atmospheric effects
 	+ Increased breaking force/torque of all 2.5m nacelles
 	+ Increased BROADSWORD thrust to 530/820 from 490/720, increased vacum Isp slightly
 	+ Increased CUTLASS thrust to 470/700 from 430/670, increased rocket Isp to 225/345 from 185/340
 	+ Fixed some bugs in the cockpit IVAs. Still not perfect but at least they're less obvious now.
* 2016-0715: 2.2.1 (ChrisAdderley) for KSP 1.1.3
 	+ Fixed fuel capacity for basic Mk4 fuselages
 	+ Fixed CTT patch assigning some parts to nonexistant nodes
 	+ Fixed an issue where multiple blade rotators would conflict on lift fans
* 2016-0630: 2.2.0 (ChrisAdderley) for KSP 1.1.3
	+ KSP 1.1.3 update
	+ Upgraded bundled ModuleManager to 2.6.25
	+ Upgraded bundled Firespitter 1.4.1
	+ Switched from BDAnimationModules to DeployableEngines for all engine animation functionality
	+ Switched from IFS to B9PartSwitch for all model/part switching functionality
	+ Added IVA blocking meshes for both Mk4 cockpits and the crew cabin
	+ Added sound loops for turboprops
	+ Added USI Life Support compatibility patch
	+ Added HVR-ONE, HVR-TWO, HVR-THREE heavy lift fans
	+ Added Mk4 'Skate' Tailpiece
	+ Added ARV-50-2 Heavy Symmetric RCS Blister
	+ Added Mk2A 100X Aviation Fuel Tank
	+ Tweaked CUTLASS and BROADSWORD engine FX
	+ Fixed orientation of the surface attach node on the 2.5m precooler and fuel tanks
	+ Fixed CLS passability for the Thunderhawk cockpit
	+ Added workaround for Thunderhawk cockpit's integrated docking port and control directions
	+ Fixed propeller spinners being shown on models in the parts list
	+ Made a WIP part invisible in the research facility and in search
	+ Corrected a few inconsistent masses in some parts
* 2016-0103: 2.1.1 (ChrisAdderley) for KSP 1.0.5
	+ Fix to thermal values for most parts
	+ Fixed incorrect BDAnimationModules version
	+ Fixed FAR patch for crew cabin
	+ Fixed duplicate lift module in crew cabin
* 2016-0102: 2.1.0 (ChrisAdderley) for KSP 1.0.5 PRE-RELEASE
	+ KSP 1.05
	+ Added MiniAVC versioning
	+ Converted cargo ramp to use stock module (deprecated old one)
	+ All jet engines now use the correct 1.05 fuel flow mode
	+ All cargo bays can now use the tweakable opening module
	+ All engines now use the delayed animation module for heat animations
	+ Adjusted intake effectiveness to match 1.05 intakes
	+ Respecced and remodeled Arcadia turbojet as a medium-performance jet with thrust reversers
	+ Added Mk4 Vulture cockpit - pointy cockpit with integrated docking port
	+ Added CUTLASS: 2.5m high-efficiency RAPIER-style engine
	+ Added Valkyrie turboramjet: high performance high altitude 2.5m engine 
	+ Added Kerboshov D27 Propfan engine (efficient heavy propeller engine)
	+ Added APR-4000 Buzzsaw Turboprop engine (powerful heavy propeller engine)
	+ Added 3 lengths of basic 2.5m liquid fuel tanks (LF, LF/O, structural)
	+ Increased occlusion detection radius for all cargo bays
	+ Fixed facing of SCIMITAR's rear attach node
	+ Fixed RCS blister's surface attach node
	+ Reduced the spooling time on the Yellowjacket engine
* 2015-0724: 2.0.0 (ChrisAdderley) for KSP 1.0.4
	+ Remodel and retexture of all 1.x generation parts parts. Notable changes:
	+ Increase in size of approximately 25% for all parts
	+ Mk4 Cockpit and most adapters now have 1.25m attach nodes on each side to mount new shoulder pieces or standard 1.25m parts
	+ Adapters have been reworked to different sizes due to size increases
	+ Fuselages and cargo bays are now available in 1x, 2x and 4x sizes, with lengths matching Mk3 parts
	+ Most fuel-containing parts can now switch fuels in the VAB (usually between LF, LF/O, LF/MP and LF/O/MP)
	+ Service bay has been reworked, now carries less RCS fuel, but has openable hatches and is better for storage
	+ Many parts are now hollow to work better with cargo stowage
	+ Yellowjacket VTOL engine now has shroud, opens and closes when active/shutdown
	+ New Parts:
		- KE-90 Turbofan Engine: 2.5m basic jet engine
		- KE-4 Turbojet Engine: 2.5m high performance engine
		- B.R.O.A.D.S.W.O.R.D Multimode Engine: 2.5m multimodal engine
		- Advanced Precooler
		- Heavy Engine Nacelle
		- Heavy Engine Nacelle XL
		- Large Turbofan Intake
		- Advanced Shock Intake
		- Mk4 Aerodynamic Shoulder
		- Mk4 Shoulder Intake
		- Mk4 Orbital Maneuvering Shoulder
		- Mk4 Ventral Cargo Bays (3 sizes)
		- Heavy RCS Blister
* 2014-1215: 1.1.2 (ChrisAdderley) for KSP 0.25
	+ Fixed a major bug in the MM configs that would cause all parts to always have their FAR/DRE/TS patches loaded
	+ Fixed low impact tolerance of Mk4 Cockpit, Crew Cabin and Drone Core
	+ Fixed the dry mass of the Extended LFO and LF fuselages being 1/3 too low
	+ Fixed a few more FAR omissions
	+ Fixed attach symmetry on the Mk4 Triple Adapter
	+ Improved the look of the Mk4 Cockpit's intakes
	+ Disembarking from the Mk4 Cockpit should now be prioritized to the front hatch
	+ Hatches from the Crew Cabin and Cockpit should be easier to click on
* 2014-1211: 1.1.1 (ChrisAdderley) for KSP 0.25
	+ Fixed DRE patch for SCIMITARs being wrong
	+ Changed how MM patches for mod compatability are applied for easier end-user tweaking
	+ Increased area of Heavy Structural Intakes slightly (about 1.25x as effective)
	+ Increased strength of Cargo Bay connections
	+ Added intakes to the Mk4 Cockpit (~1 Shock Cone intake effectiveness)
	+ Added custom SFX to the SCIMITAR
	+ Added Yellowjacket VTOL jet engine - high thrust, overheats easily
* 2014-1208: 1.1.0 (ChrisAdderley) for KSP 0.25
	+ Added basic Deadly Reentry MM configs
	+ Added basic TweakScale MM configs
	+ Fixed a clipping error in the Mk4 RPM Cockpit IVA
	+ Fixed intake area for Heavy Structural Intakes
	+ Adjusted thrust and thrust curve for SCIMITAR engine in FAR/NEAR
	+ Adjusted and optimized colliders on LFO/LF Fuselages, Cargo Bay, Crew Cabin, Cockpit, Service Compartment, Drone Core, Adapters, Tails
	+ Adjusted all cargo bay floors, hopefully things will fall through less frequently
	+ Redid colliders on cargo doors and service compartment top, should be more symmetrical now
	+ All Mk4 part connections now use size 3 attach nodes instead of size 2 (should decrease wobble)
	+ Cargo tail, all adapters, all tail pieces, nosecones can no longer be surface attached
	+ Fixed surface attach node on Crew Cabin, LF Fuselage, LFO Fuselage, Cargo Bay
	+ Parts can no longer be attached to the Mk4 docking nosecone
	+ Added missing description to Mk4 nosecone
	+ Fixed a mesh seam on the Mk4 Triple Adapter
	+ Added Extended Mk4 Cargo Bay (triple-length cargo bay)
	+ Added Mk4 Extended Liqid Fuel Fuselage
	+ Added Mk4 Extended LF+O Fuselage
* 2014-1201: 1.0.0 (ChrisAdderley) for KSP 0.25
	+ No changelog provided
* 2014-1129: 0.05 (ChrisAdderley) for KSP 0.25 PRE-RELEASE
	+ RC1
	+ Added IVA for Mk4 Cockpit
	+ Added CLS configs
	+ Added two wing engine pods
	+ Added SCIMITAR high-thrust multimode engine
	+ Adjusted lifting body lift and AoA drag accross the board
	+ Added small amount of LFO to Cargo Bay and Cargo Tail
	+ Fixed FAR config (I think), added support for NEAR
	+ Disabled attachment on moving components of Cargo Tail
* 2014-1114: 0.04 (ChrisAdderley) for KSP 0.25 PRE-RELEASE
	+ New parts, new textures, tweaks to parts.
* 2014-1028: 0.03 (ChrisAdderley) for KSP 0.25 PRE-RELEASE
	+ Textures for many parts, new parts
* 2014-1018: 0.02 (ChrisAdderley) for KSP 0.25 PRE-RELEASE
	+ Added nosecones, new adapter. Started unwrapping parts. Minor rebalance of part stats.
* 2014-1012: 0.01 (ChrisAdderley) for KSP 0.25 PRE-RELEASE
	+ Test release, with very basic, textureless initial parts.
