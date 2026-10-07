# Awesome 3D Printers

A curated catalog of open-design and community-documented FDM printers to build, modify, or study. Each design has **one catalog row**. The printer name links to its project repository when available, otherwise to the creator's project page or a useful community reference. Maker and family labels help you find related designs without repeating rows.

**Photos:** 📷 marks a planned image. Images can be added after checking permission, source, and consistent sizing. **Resources:** STEP/CAD links point to source files or their containing folder when available; “Files” may contain printable models without STEP. A dash means a useful direct resource link has not yet been confirmed. Build cost, difficulty, and project status change, so the short descriptions are starting points rather than rankings.

## Contents

- [Start here](#start-here)
- [Build from scratch](#build-from-scratch)
  - [CoreXY](#corexy)
  - [Cartesian / CoreXZ](#cartesian--corexz)
  - [Delta](#delta)
  - [Other motion systems](#other-motion-systems)
- [Conversions](#conversions)
- [Historical designs](#historical-designs)
- [Browse by maker or family](#browse-by-maker-or-family)

## Start here

A few different reasons to choose a first project; these point to the full catalog rows below.

- **Small, approachable build:** [Kappy](#kappy) has a creator-supplied manual and BOM.
- **Mostly printed CoreXY:** [Rook MK1](#rook-mk1) is a compact introduction to CoreXY.
- **Documented full-size CoreXY:** [Voron Trident](#voron-trident) has released CAD and an assembly manual.
- **Try a delta:** [Delta Flyer](#delta-flyer) pairs a small delta with a build manual.
- **Reuse existing printers:** [Duender](#duender) converts parts from two Ender-3 machines into a CoreXY.
- **Explore a different layout:** [Lemontron](#lemontron) is a portable inverted printer; check the revision notes before building.

## Build from scratch

The primary sections describe XY motion, with special layouts called out in the **Build type** column. “From scratch” includes projects that offer optional kits.

### CoreXY

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="voron-2-4"></a>[**Voron 2.4**](https://github.com/VoronDesign/Voron-2) · *Voron family* — large enclosed design with a moving gantry. | CoreXY | [CAD](https://github.com/VoronDesign/Voron-2/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-2/blob/HEAD/Manual/Assembly_Manual_2.4r2.pdf) |
| 📷 | <a id="voron-trident"></a>[**Voron Trident**](https://github.com/VoronDesign/Voron-Trident) · *Voron family* — fixed gantry and independently driven Z bed. | CoreXY | [CAD](https://github.com/VoronDesign/Voron-Trident/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-Trident/blob/HEAD/Manual/Assembly_Manual_Trident.pdf) |
| 📷 | <a id="voron-v0"></a>[**Voron V0**](https://github.com/VoronDesign/Voron-0) · *Voron family* — compact enclosed CoreXY platform. | CoreXY | [CAD](https://github.com/VoronDesign/Voron-0/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-0/blob/HEAD/Manuals/VORON_V0.2r1_Assembly_Manual.pdf) |
| 📷 | <a id="hypercube-evolution"></a>[**HyperCube Evolution**](https://www.thingiverse.com/thing:2254103) · *SCOTT_3D* — aluminum-extrusion evolution of the HyperCube. | CoreXY | [Files](https://www.thingiverse.com/thing:2254103/files) |
| 📷 | <a id="hypercube"></a>[**HyperCube**](https://www.thingiverse.com/thing:1752766) · *Tech2C* — influential extrusion-frame DIY CoreXY. | CoreXY | [Files](https://www.thingiverse.com/thing:1752766/files) |
| 📷 | <a id="blv-mgn-cube"></a>[**BLV MGN Cube**](https://www.thingiverse.com/thing:3382718) · *BLV* — cube design built around linear rails. | CoreXY | [Files](https://www.thingiverse.com/thing:3382718/files) |
| 📷 | <a id="ratrig-v-core-3"></a>[**Rat Rig V-Core 3**](https://github.com/Rat-Rig/V-core-3) · *Rat Rig family* — scalable extrusion-frame printer. | CoreXY | [CAD](https://github.com/Rat-Rig/V-core-3/tree/HEAD/cad) · [Docs](https://github.com/Rat-Rig/V-core-3/tree/HEAD/docs) |
| 📷 | <a id="hevort"></a>[**HevORT**](https://github.com/MirageC79/HevORT) · *MirageC79* — large-format, high-performance community design. | CoreXY | [Docs](https://github.com/MirageC79/HevORT/tree/HEAD/docs) · [BOM](https://github.com/MirageC79/HevORT/tree/HEAD/bom) |
| 📷 | <a id="vzbot"></a>[**VzBot Vz330**](https://github.com/VzBoT3D/VzBoT-Vz330) · *VzBot family* — high-speed design with AWD variants. | CoreXY | [CAD](https://github.com/VzBoT3D/VzBoT-Vz330/tree/HEAD/CAD) · [Build guide](https://github.com/VzBoT3D/VzBoT-Vz330/tree/HEAD/Build%20guide-manual) |
| 📷 | <a id="railcore-ii"></a>[**RailCore II**](https://github.com/railcore/parts) · *RailCore family* — rail-guided, rigid CoreXY. | CoreXY | [STEP](https://github.com/railcore/parts/tree/HEAD/STEP) |
| 📷 | <a id="d-bot"></a>[**D-Bot**](https://www.thingiverse.com/thing:1001065) — extrusion-frame DIY design with a large modding community. | CoreXY | [Files](https://www.thingiverse.com/thing:1001065/files) |
| 📷 | <a id="c-bot"></a>[**C-Bot**](https://www.thingiverse.com/thing:500041) — uses V-slot wheels and extrusion for guided motion. | CoreXY | [Files](https://www.thingiverse.com/thing:500041/files) |
| 📷 | <a id="seckit-sk-tank"></a>[**SecKit SK-Tank**](https://github.com/SecKit/SK-Tank) · *SecKit family* — all-metal frame kit design. | CoreXY | [Manual](https://sites.google.com/view/seckit-wiki/sk-tank-350x350x400) |
| 📷 | <a id="seckit-sk-go"></a>[**SecKit SK-Go**](https://github.com/SecKit/SK-Go_SK-Mini) · *SecKit family* — extrusion-frame design with a self-sourcing path. | CoreXY | [STEP](https://github.com/SecKit/SK-Go_SK-Mini/tree/HEAD/Go3%20%28AE2-310eu%20v3%29/STEP%20files) · [Manual](https://sites.google.com/view/seckit-wiki/sk-go-310x310x350) |
| 📷 | <a id="rook-mk1"></a>[**Rook MK1**](https://www.printables.com/model/387431-rook-mk1-3d-printer) · *Rolohaun / Rook family* — mostly printed, inexpensive 120 mm CoreXY. | CoreXY | [Manual](https://drive.google.com/file/d/1Nc4iz1Pq0eWxs1gyqM3IEtTrQ-v9zu7r/view) · [STEP (older release)](https://github.com/rolohaun/Rook/blob/HEAD/CAD/Rook_MK1.step) |
| 📷 | <a id="rook-2020-mk1"></a>[**Rook 2020 MK1**](https://www.printables.com/model/447255-rook-2020-mk1) · *Rolohaun / Rook family* — Rook layout with 2020 extrusion. | CoreXY | [Files](https://www.printables.com/model/447255-rook-2020-mk1/files) |
| 📷 | <a id="rook-2020-mk2"></a>[**Rook 2020 MK2**](https://www.printables.com/model/798733-rook-2020-mk2) · *Rolohaun / Rook family* — later extrusion-frame Rook release. | CoreXY | [BOM](https://docs.google.com/spreadsheets/d/1k5knQOW3YX01BzTAEe6YCPVp2iNppOEKYJrqB6Ln_Wk/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/ccf745a3232adcedee163729/w/32082f8119c17ae81d2ba337/e/7da9f0f6822236e671d3e7e1) |
| 📷 | <a id="simplecore"></a>[**SimpleCore**](https://www.printables.com/model/1473500-simplecore) · *Rolohaun* — another compact CoreXY approach. | CoreXY | [Files](https://www.printables.com/model/1473500-simplecore/files) · [STEP (older MK1)](https://github.com/rolohaun/SimpleCore/blob/HEAD/CAD/SimpleCore%20MK1.step) |
| 📷 | <a id="panda-mini"></a>[**Panda Mini**](https://www.printables.com/model/571947-panda-mini-corexy-3d-printer) · *Rolohaun* — small-format CoreXY. | CoreXY | [Files](https://www.printables.com/model/571947-panda-mini-corexy-3d-printer/files) |
| 📷 | <a id="bastion"></a>[**Bastion**](https://www.printables.com/model/748800-bastion-3d-printer) · *Rolohaun* — triple independent Z and a Prusa Mini bed. | CoreXY | [BOM](https://docs.google.com/spreadsheets/d/1l0jujA7NeqoZIqLFWoQa9GS_q04f8Wfkya9Il5d2ubA/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/256743a99b7cb9b4ae8f45f9/w/29df722021bf3c0e59d7c8ae/e/ff9493cea103644b334a3c7a) |
| 📷 | <a id="fenrir"></a>[**Fenrir**](https://www.makerviking.com/wiki/fenrir-corexy-3d-printer) · *MakerViking* — mostly printed CoreXY prototype; confirm file release before planning a build. | CoreXY / prototype | [Creator video](https://www.youtube.com/watch?v=qJi_0GzD9xU) |
| 📷 | <a id="the100"></a>[**THE100**](https://github.com/mszturc/THE100) · *Matt the Printing Nerd* — fast design with a printed frame. | CoreXY | [STEP](https://github.com/mszturc/THE100/blob/HEAD/STEP/The%20100%20v1.1.step) · [Docs](https://github.com/mszturc/THE100/tree/HEAD/Docs) |
| 📷 | <a id="t250"></a>[**T250**](https://github.com/mszturc/T250) · *Matt the Printing Nerd* — larger high-speed successor to THE100. | CoreXY | [STEP](https://github.com/mszturc/T250/blob/HEAD/CAD/T250-v1.0-final.step) · [Docs](https://github.com/mszturc/T250/tree/HEAD/Docs) |
| 📷 | <a id="micron"></a>[**Micron**](https://github.com/PrintersForAnts/Micron) · *Printers for Ants* — miniature Voron-inspired enclosed build. | CoreXY | [CAD](https://github.com/PrintersForAnts/Micron/tree/HEAD/CAD) · [Manual](https://github.com/PrintersForAnts/Micron/blob/HEAD/Documentation/Micron_R1_Manual_WIP.pdf) |
| 📷 | <a id="salad-fork"></a>[**Salad Fork**](https://github.com/PrintersForAnts/Salad_Fork) · *Printers for Ants* — small Trident-inspired build. | CoreXY | [CAD](https://github.com/PrintersForAnts/Salad_Fork/tree/HEAD/CAD) · [Manual](https://github.com/PrintersForAnts/Salad_Fork/blob/HEAD/Salad%20Fork%20Manual.pdf) |
| 📷 | <a id="jubilee"></a>[**Jubilee**](https://github.com/machineagency/jubilee) · *Machine Agency* — open tool-changing platform. | CoreXY / toolchanger | [STEP](https://github.com/machineagency/jubilee/blob/HEAD/frame/cads/STEP/jubilee.STEP) |
| 📷 | <a id="valkyrie"></a>[**Project Valkyrie**](https://github.com/3D-Experiments/Project-Valkyrie) · *3D Experiments* — inverted CoreXY for experimental builds. | Inverted CoreXY | [Design library](https://github.com/3D-Experiments/Project-Valkyrie/tree/HEAD/Document%20Library) |

### Cartesian / CoreXZ

Includes independently driven X/Y layouts; the specific motion system is stated in each row.

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="prusa-i3"></a>[**Original Prusa i3**](https://github.com/prusa3d/Original-Prusa-i3) · *Prusa family* — an influential open-design moving-bed platform. | Cartesian | [Parts and source](https://github.com/prusa3d/Original-Prusa-i3) |
| 📷 | <a id="rook-mk2"></a>[**Rook MK2**](https://www.printables.com/model/1644597-rook-mk2) · *Rolohaun / Rook family* — fully printed frame; creator labels this a beta release. | Cartesian | [BOM](https://docs.google.com/spreadsheets/d/18EqrtU4kwdb6v4gPMTdCcCdBVbxlF5-EhFE0hZtxHoA/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/5010167e95003ed32232fd0e/w/756fbf38edf59fb734f7365c/e/e647ceb1e4681ba492e8722b) |
| 📷 | <a id="kappy"></a>[**Kappy**](https://www.printables.com/model/625544-kappy-3d-printer) · *Rolohaun* — small, beginner-oriented DIY printer. | Cartesian | [Manual](https://drive.google.com/file/d/1iMX36I9zHaRenk27AsYJOz9wUkhZm12h/view) · [BOM](https://docs.google.com/spreadsheets/d/10yJ0s7zZR3LtqlApnVSDP2MTe3I9gViXxYyVxZ6Vb1I/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/e3d1e390ee25e4cecb91b755/w/71cf613e30e4a447f8845523/e/ca80937f1c3e35dd2362d739) |
| 📷 | <a id="annex-k3"></a>[**Annex K3 / Gasherbrum**](https://github.com/Annex-Engineering/Gasherbrum-K3) · *Annex Engineering* — small enclosed machine with separate X and Y drives. | CartesianXY | [Release files](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/HEAD/Release_1_2) |
| 📷 | <a id="voron-switchwire"></a>[**Voron Switchwire**](https://github.com/VoronDesign/Voron-Switchwire) · *Voron family* — belt-driven CoreXZ layout. | CoreXZ | [CAD](https://github.com/VoronDesign/Voron-Switchwire/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-Switchwire/blob/HEAD/Manuals/Assembly_Manual_SW.pdf) |
| 📷 | <a id="lh-stinger"></a>[**LH Stinger**](https://github.com/lhndo/LH-Stinger) · *LHndo* — performance-focused moving-bed design. | Cartesian | [CAD](https://github.com/lhndo/LH-Stinger/tree/HEAD/CAD) · [Wiki](https://github.com/lhndo/LH-Stinger/wiki) |

### Delta

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="delta-flyer"></a>[**Delta Flyer**](https://www.printables.com/model/1327596-delta-flyer-3d-printer) · *Rolohaun / Kanrog* — compact delta with linear rails and a published manual. | Delta | [Manual](https://kanrog.github.io/Delta-Flyer/) · [BOM](https://docs.google.com/spreadsheets/d/1400rbdxxYbIA15yIi4UiYHQk1Ul_DCyP7nSTH7CUpFE/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/de9bc61850e74a1717307838/w/2a32f2b0d6edf7beeb9fcbf7/e/392043168b1092bab001d0df) |
| 📷 | <a id="min-micro-delta"></a>[**MIN Micro Delta**](https://www.printables.com/model/857334-min-micro-delta-3d-printer) · *Rolohaun* — a very small delta project. | Delta | [Files](https://www.printables.com/model/857334-min-micro-delta-3d-printer/files) |

### Other motion systems

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="hangprinter"></a>[**Hangprinter**](https://github.com/tobbelobb/hangprinter) · *Torbjørn Ludvigsen* — cable-suspended, frameless printer. | Cable-driven | [Project files](https://github.com/tobbelobb/hangprinter) |
| 📷 | <a id="white-knight-belt"></a>[**White Knight Belt**](https://www.thingiverse.com/thing:3977443) — DIY continuous-print belt concept. | Belt printer | [Files](https://www.thingiverse.com/thing:3977443/files) |
| 📷 | <a id="babybelt-pro"></a>[**BabyBelt Pro**](https://github.com/RobMink/BabyBeltPro) · *Rob Mink* — compact belt printer. | Belt printer | [STEP](https://github.com/RobMink/BabyBeltPro/blob/HEAD/CAD/BBProV2POINT6.stp) · [Build guide](https://github.com/RobMink/BabyBeltPro/blob/HEAD/documentation/bbpv2_build_guide.md) |
| 📷 | <a id="infini-z"></a>[**Infini-Z**](https://projectquine.substack.com/p/the-first-infini-z) · *SunShine / Andras* — experimental self-climbing Z axis. | Climbing Z | [Model files](https://cults3d.com/en/3d-model/tool/infini-z-3d-printer) |
| 📷 | <a id="positron-v3"></a>[**Positron V3**](https://github.com/Kralyn/PositronV3) · *Kralyn* — folding, inverted portable printer. | Inverted / folding | [CAD](https://github.com/Kralyn/PositronV3/tree/HEAD/CAD%20%20files) |
| 📷 | <a id="lemontron"></a>[**Lemontron**](https://lemontron.com/lemontron-rev-e/) · *Lemontron* — portable inverted design; Rev E files are released, with the earlier guide used for assembly. | Inverted / portable | [Rev E files](https://lemontron.com/lemontron-rev-e/printed-parts/) · [Rev A build guide](https://lemontron.com/lemontron-rev-a/build-guide/) · [BOM](https://lemontron.com/lemontron-rev-e/bom/) · [Creator video](https://www.youtube.com/watch?v=n6l3GvkE4QU) |

## Conversions

These reuse a donor printer or modify an existing printer family. Check the exact donor model and revision before ordering parts.

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="duender"></a>[**Duender**](https://github.com/Irbis3D/Duender) · *Irbis3D* — turns parts from two Ender-3 printers into one CoreXY. | Ender-3 → CoreXY | [STEP kits](https://github.com/Irbis3D/Duender/tree/HEAD/STEP%20KITS) · [Manual](https://github.com/Irbis3D/Duender/tree/HEAD/Manual) |
| 📷 | <a id="ender-3-ng"></a>[**Ender-3 NG**](https://www.printables.com/model/922401-ender-3-ng-v12-corexy-conversion) · *RH3D* — Ender-3 CoreXY conversion with a dedicated guide. | Ender-3 → CoreXY | [Files](https://rh3d.xyz/E3NG_v1_2/standard/files) · [Build guide](https://rh3d.xyz/E3NG_v1_2/standard/build_guide) |
| 📷 | <a id="mercury-one"></a>[**Mercury One**](https://github.com/ZeroGDesign/MercuryOne) · *ZeroG* — CoreXY conversion for Ender-5 family machines. | Ender-5 → CoreXY | [CAD](https://github.com/ZeroGDesign/MercuryOne/tree/HEAD/CAD) · [Mercury One.1 build guide](https://docs.zerog.one/manual/build/mercury_eva) |
| 📷 | <a id="double-dragon"></a>[**Double Dragon**](https://github.com/zruncho3d/double-dragon) · *zruncho3d* — Voron V0-derived dual-extrusion experiment. | V0-derived IDEX mod | [CAD](https://github.com/zruncho3d/double-dragon/tree/HEAD/CAD) |
| 📷 | <a id="dueling-zero"></a>[**Dueling Zero**](https://github.com/zruncho3d/DuelingZero) · *zruncho3d* — Voron V0-derived dual-gantry project. | V0-derived dual-gantry mod | [CAD](https://github.com/zruncho3d/DuelingZero/tree/HEAD/CAD) · [Instructions](https://github.com/zruncho3d/DuelingZero/blob/HEAD/INSTRUCTIONS.md) |

## Historical designs

Foundational and older community designs remain useful for learning and restoration. A wiki page here may document the design without offering a current, complete build package.

| Photo | Printer and why it’s interesting | Build type | Resources |
| --- | --- | --- | --- |
| 📷 | <a id="darwin"></a>[**Darwin**](https://reprap.org/wiki/Darwin) · *RepRap* — one of the earliest self-replicating printer designs. | Cartesian | — |
| 📷 | <a id="mendel"></a>[**Mendel**](https://reprap.org/wiki/Mendel) · *RepRap* — influential second-generation RepRap. | Cartesian | — |
| 📷 | <a id="prusa-mendel-i2"></a>[**Prusa Mendel i2**](https://reprap.org/wiki/Prusa_Mendel) · *Prusa / RepRap* — an early simplification of Mendel. | Cartesian | — |
| 📷 | <a id="prusa-i3-early"></a>[**Prusa i3 (early)**](https://reprap.org/wiki/Prusa_i3) · *Prusa / RepRap* — early i3 documentation for the design lineage. | Cartesian | — |
| 📷 | <a id="huxley"></a>[**Huxley**](https://reprap.org/wiki/Huxley) · *RepRap* — compact early RepRap. | Cartesian | — |
| 📷 | <a id="wallace"></a>[**Wallace**](https://reprap.org/wiki/Wallace) · *RepRap* — minimalist early design. | Cartesian | — |
| 📷 | <a id="tantillus"></a>[**Tantillus**](https://reprap.org/wiki/Tantillus) · *RepRap* — small enclosed printer with printed structural parts. | Cartesian | — |
| 📷 | <a id="ultimaker-original"></a>[**Ultimaker Original**](https://github.com/Ultimaker/UltimakerOriginal) · *Ultimaker* — open-design wooden-frame machine. | Cartesian | [BOM](https://github.com/Ultimaker/UltimakerOriginal/tree/HEAD/BOM) |
| 📷 | <a id="mendelmax"></a>[**MendelMax**](https://github.com/maxbots/MendelMax) · *Maxbots* — aluminum-extrusion Mendel variant. | Cartesian | [STEP](https://github.com/maxbots/MendelMax/blob/HEAD/MendelMax.stp) · [Wiki](https://reprap.org/wiki/MendelMax) |
| 📷 | <a id="mendel90"></a>[**Mendel90**](https://github.com/nophead/Mendel90) · *nophead* — sheet-frame Mendel variant. | Cartesian | [Project files](https://github.com/nophead/Mendel90) |
| 📷 | <a id="smartrap"></a>[**Smartrap**](https://reprap.org/wiki/Smartrap_mini) — compact, low-part-count RepRap design. | Cartesian | — |
| 📷 | <a id="snappy"></a>[**Snappy**](https://github.com/revarbat/snappy-reprap) · *revarbat* — mostly printed, snap-together RepRap. | Cartesian | [Docs](https://github.com/revarbat/snappy-reprap/tree/HEAD/docs) |
| 📷 | <a id="foldarap"></a>[**FoldaRap**](https://github.com/EmmanuelG/Foldarap) · *Emmanuel Gilli* — folding portable RepRap. | Cartesian / folding | [Source files](https://github.com/EmmanuelG/Foldarap) |
| 📷 | <a id="itopie"></a>[**ITopie**](https://reprap.org/wiki/ITopie) — older framed RepRap design. | Cartesian | — |
| 📷 | <a id="rostock"></a>[**Rostock**](https://reprap.org/wiki/Rostock) · *RepRap* — foundational parallel-arm delta. | Delta | — |
| 📷 | <a id="kossel"></a>[**Kossel**](https://reprap.org/wiki/Kossel) · *RepRap* — a widely replicated delta lineage. | Delta | — |
| 📷 | <a id="cerberus"></a>[**Cerberus**](https://reprap.org/wiki/Cerberus) · *RepRap* — older delta variant. | Delta | — |
| 📷 | <a id="lisa-simpson"></a>[**LISA Simpson**](https://reprap.org/wiki/LISA_Simpson) · *Simpson family* — experimental grounded delta variant. | Grounded delta | — |
| 📷 | <a id="gus-simpson"></a>[**GUS Simpson**](https://reprap.org/wiki/GUS_Simpson) · *Simpson family* — experimental grounded delta prototype. | Grounded delta | — |
| 📷 | <a id="tevo-little-monster"></a>[**Tevo Little Monster**](https://github.com/Homers3D/Tevo-Little-Monster) · *community reference* — large commercial delta with owner-maintained firmware and documents. | Delta | [Firmware and docs](https://github.com/Homers3D/Tevo-Little-Monster) |
| 📷 | <a id="cherry-pi-delta"></a>[**Cherry Pi Delta**](https://www.thingiverse.com/thing:210028) — older community delta design. | Delta | [Files](https://www.thingiverse.com/thing:210028/files) |
| 📷 | <a id="reprap-morgan"></a>[**RepRap Morgan**](https://reprap.org/wiki/RepRap_Morgan) · *RepRap* — articulated-arm alternative to Cartesian gantries. | SCARA | — |
| 📷 | <a id="wally"></a>[**Wally**](https://reprap.org/wiki/Wally) · *RepRap* — compact arm-based experiment. | SCARA | — |
| 📷 | <a id="r360-polar"></a>[**R-360 Polar**](https://reprap.org/wiki/R_360) · *RepRap* — radial/polar motion experiment. | Polar | — |
| 📷 | <a id="tripteron"></a>[**Tripteron**](https://reprap.org/wiki/Tripteron) · *RepRap* — three orthogonal parallel arms. | Parallel kinematics | — |

## Browse by maker or family

The same printer appears only once above. These links jump to its row; use your browser's page search for smaller maker tags.

- **[Rolohaun / Rook](https://www.printables.com/@Rolohaun/models):** [Rook MK1](#rook-mk1) · [Rook MK2](#rook-mk2) · [Rook 2020 MK1](#rook-2020-mk1) · [Rook 2020 MK2](#rook-2020-mk2) · [SimpleCore](#simplecore) · [Panda Mini](#panda-mini) · [Bastion](#bastion) · [Kappy](#kappy) · [MIN Micro Delta](#min-micro-delta) · [Delta Flyer](#delta-flyer)
- **Voron:** [V0](#voron-v0) · [Trident](#voron-trident) · [2.4](#voron-2-4) · [Switchwire](#voron-switchwire). The [Double Dragon](#double-dragon) and [Dueling Zero](#dueling-zero) are related V0-derived mods.
- **Printers for Ants:** [Micron](#micron) · [Salad Fork](#salad-fork)
- **SecKit:** [SK-Go](#seckit-sk-go) · [SK-Tank](#seckit-sk-tank)
- **Prusa / RepRap:** [Original Prusa i3](#prusa-i3) · [early i3](#prusa-i3-early) · [Prusa Mendel i2](#prusa-mendel-i2)
- **Matt the Printing Nerd:** [THE100](#the100) · [T250](#t250)

### Suggest a printer or resource

A useful addition has a specific printer design and a project page, plus a short reason it is interesting. Direct links to a build guide, BOM, STEP/CAD, and creator video are welcome when available. For photos, include the source and reuse permission. Avoid broad homepages, dead links, duplicate listings, and unverified claims of “best” or “cheapest.”

The former list is preserved in [`bak-README.md`](bak-README.md). Its **Sethi H-Bot** link no longer resolves, and its **RepRap H-Bot Project** link describes a motion system rather than a specific printer; both remain in the backup pending a suitable project source. The old **Saturn Delta** link could not be tied to a specific delta printer, and **Sixi** is a robotic arm rather than a printer; those entries also remain in the backup.
