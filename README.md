# Awesome 3D Printers

A curated catalog of open-design and community-documented FDM printers to build, modify, or study. Each design has **one catalog row**. The printer name links to its project repository when available, otherwise to the creator's project page or a useful community reference. Maker and family labels help you find related designs without repeating rows.

**Photos:** 📷 marks a planned image. Images can be added after checking permission, source, and consistent sizing. **Resources:** STEP/CAD links point to source files or their containing folder when available; “Files” may contain printable models without STEP. A dash means a useful direct resource link has not yet been confirmed. Build cost, difficulty, and project status change, so the short descriptions are starting points rather than rankings.

**Sizes:** All figures are millimetres. Build volume is printable X × Y × Z, not the physical bed size. Exterior size is the reported body or frame width × depth × height; it may exclude a spool, moving-bed clearance, cables, or enclosure extras. `?` means that axis was not confirmed, and `—` means no trustworthy figure was found. Variant names keep their build and exterior measurements paired. `†` marks approximate or revision-dependent figures from the [MaybeCube](https://github.com/martinbudden/MaybeCube#comparisons) or [BabyCube](https://github.com/martinbudden/BabyCube#comparisons) comparison tables; check the current maker files before planning a space. MaybeCube's own overview and variant table differ for MC350, so the row uses its labelled variant table. For circular deltas, `Ø` is print diameter. For belt printers, an open-ended print length is not converted into a finite volume.

## Contents

- [Start here](#start-here)
- [Build from scratch](#build-from-scratch)
  - [CoreXY](#corexy)
  - [Cartesian / CoreXZ](#cartesian--corexz)
  - [Delta](#delta)
  - [Other motion systems](#other-motion-systems)
- [Conversions](#conversions)
- [Historical designs](#historical-designs)
- [Browse mini and portable printers](#browse-mini-and-portable-printers)
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

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="voron-2-4"></a>[**Voron 2.4**](https://github.com/VoronDesign/Voron-2) · *Voron family* — large enclosed design with a moving gantry. | CoreXY | 250: 250×250×230†<br>300: 300×300×280†<br>350: 350×350×330† | 250: 410×410×430†<br>300: 460×460×480†<br>350: 510×510×530† | [CAD](https://github.com/VoronDesign/Voron-2/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-2/blob/HEAD/Manual/Assembly_Manual_2.4r2.pdf) |
| 📷 | <a id="voron-trident"></a>[**Voron Trident**](https://github.com/VoronDesign/Voron-Trident) · *Voron family* — fixed gantry and independently driven Z bed; current R2 release revises XY and Z motion. | CoreXY | 250: 250×250×250†<br>300: 300×300×250†<br>350: 350×350×250† | 250: 410×410×500†<br>300: 460×460×500†<br>350: 510×510×500† | [CAD](https://github.com/VoronDesign/Voron-Trident/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-Trident/blob/HEAD/Manual/Assembly_Manual_Trident.pdf) · [R2 notes](https://forum.vorondesign.com/threads/voron-trident-r2-is-out.17490/) |
| 📷 | <a id="voron-v0"></a>[**Voron V0**](https://github.com/VoronDesign/Voron-0) · *Voron family* — compact enclosed CoreXY platform. | CoreXY | 120×120×120† | 230×230×280† | [CAD](https://github.com/VoronDesign/Voron-0/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-0/blob/HEAD/Manuals/VORON_V0.2r1_Assembly_Manual.pdf) |
| 📷 | <a id="hypercube-evolution"></a>[**HyperCube Evolution**](https://www.thingiverse.com/thing:2254103) · *SCOTT_3D* — aluminum-extrusion evolution of the HyperCube. | CoreXY | 300×300×300† | 480×470×500† | [Files](https://www.thingiverse.com/thing:2254103/files) |
| 📷 | <a id="hypercube"></a>[**HyperCube**](https://www.thingiverse.com/thing:1752766) · *Tech2C* — influential extrusion-frame DIY CoreXY. | CoreXY | 200×200×155† | 380×343×350† | [Files](https://www.thingiverse.com/thing:1752766/files) |
| 📷 | <a id="blv-mgn-cube"></a>[**BLV MGN Cube**](https://www.thingiverse.com/thing:3382718) · *BLV* — cube design built around linear rails. | CoreXY | 300×300×365† | 576×536×560† | [Files](https://www.thingiverse.com/thing:3382718/files) |
| 📷 | <a id="ratrig-v-core-4-1"></a>[**Rat Rig V-Core 4.1**](https://ratrig.com/products/rat-rig-v-core-4-1) · *Rat Rig family* — current large-format platform with optional Hybrid and IDEX upgrades. | CoreXY / variants | 300: 300×300×300<br>400: 400×400×400<br>500: 500×500×500 | 300: 623.2×583×785<br>400: 723.2×683×885<br>500: 823.2×783×985 | [CAD (300 CoreXY)](https://a360.co/49FDeXb) · [CAD variants](https://ratrig.com/products/rat-rig-v-core-4-1) · [Files](https://wiki.ratrig.com/products/v-core-4-1/files) · [Build guide](https://wiki.ratrig.com/products/v-core-4-1/build-guide) · [BOM](https://docs.google.com/spreadsheets/d/1lGxKfwd0G22HPD6DDV5jK_a0T9UC1q8YWn3PXyn1YvQ/edit) |
| 📷 | <a id="ratrig-v-core-3"></a>[**Rat Rig V-Core 3**](https://github.com/Rat-Rig/V-core-3) · *Rat Rig family* — earlier scalable extrusion-frame generation with its own published files. | CoreXY | 300: 300×300×300†<br>400: 400×400×400†<br>500: 500×500×500† | 300: 518×583×560†<br>400: 618×683×660†<br>500: 718×783×760† | [CAD](https://github.com/Rat-Rig/V-core-3/tree/HEAD/cad) · [Docs](https://github.com/Rat-Rig/V-core-3/tree/HEAD/docs) · [3.2H upgrade (eligible 3.1 builds)](https://ratrig.com/products/rat-rig-v-core-3-2h-upgrade-kit-from-v-core-3-1-with-enclosure-2-0) |
| 📷 | <a id="hevort"></a>[**HevORT**](https://github.com/MirageC79/HevORT) · *MirageC79* — large-format, high-performance community design. | CoreXY | 315: 315×315×340†<br>415: 415×415×440† | — | [Docs](https://github.com/MirageC79/HevORT/tree/HEAD/docs) · [BOM](https://github.com/MirageC79/HevORT/tree/HEAD/bom) |
| 📷 | <a id="vzbot"></a>[**VzBot Vz330**](https://github.com/VzBoT3D/VzBoT-Vz330) · *VzBot family* — high-speed design with AWD variants. | CoreXY | 330×330×400† | 530×500×570† | [CAD](https://github.com/VzBoT3D/VzBoT-Vz330/tree/HEAD/CAD) · [Build guide](https://github.com/VzBoT3D/VzBoT-Vz330/tree/HEAD/Build%20guide-manual) |
| 📷 | <a id="railcore-ii"></a>[**RailCore II**](https://github.com/railcore/parts) · *RailCore family* — rail-guided, rigid CoreXY. | CoreXY | 300ZL: 300×300×330†<br>300ZLT: 300×300×600† | 300ZL: 572×495×546†<br>300ZLT: 572×495×830† | [STEP](https://github.com/railcore/parts/tree/HEAD/STEP) |
| 📷 | <a id="d-bot"></a>[**D-Bot**](https://www.thingiverse.com/thing:1001065) — extrusion-frame DIY design with a large modding community. | CoreXY | — | — | [Files](https://www.thingiverse.com/thing:1001065/files) |
| 📷 | <a id="c-bot"></a>[**C-Bot**](https://www.thingiverse.com/thing:500041) — uses V-slot wheels and extrusion for guided motion. | CoreXY | — | — | [Files](https://www.thingiverse.com/thing:500041/files) |
| 📷 | <a id="seckit-sk-tank"></a>[**SecKit SK-Tank**](https://github.com/SecKit/SK-Tank) · *SecKit family* — all-metal frame kit design. | CoreXY | 350×350×400† | 560×530×710† | [Manual](https://sites.google.com/view/seckit-wiki/sk-tank-350x350x400) |
| 📷 | <a id="seckit-sk-go"></a>[**SecKit SK-Go**](https://github.com/SecKit/SK-Go_SK-Mini) · *SecKit family* — extrusion-frame design with a self-sourcing path. | CoreXY | 310×310×350† | 520×500×500† | [STEP](https://github.com/SecKit/SK-Go_SK-Mini/tree/HEAD/Go3%20%28AE2-310eu%20v3%29/STEP%20files) · [Manual](https://sites.google.com/view/seckit-wiki/sk-go-310x310x350) |
| 📷 | <a id="rook-mk1"></a>[**Rook MK1**](https://www.printables.com/model/387431-rook-mk1-3d-printer) · *Rolohaun / Rook family* — mostly printed, inexpensive 120 mm CoreXY. | CoreXY | ~120×120×100† | ~220×250×280† | [Manual](https://drive.google.com/file/d/1Nc4iz1Pq0eWxs1gyqM3IEtTrQ-v9zu7r/view) · [STEP (older release)](https://github.com/rolohaun/Rook/blob/HEAD/CAD/Rook_MK1.step) |
| 📷 | <a id="rook-2020-mk1"></a>[**Rook 2020 MK1**](https://www.printables.com/model/447255-rook-2020-mk1) · *Rolohaun / Rook family* — Rook layout with 2020 extrusion. | CoreXY | 120×120×? | — | [Files](https://www.printables.com/model/447255-rook-2020-mk1/files) |
| 📷 | <a id="rook-2020-mk2"></a>[**Rook 2020 MK2**](https://www.printables.com/model/798733-rook-2020-mk2) · *Rolohaun / Rook family* — later extrusion-frame Rook release. | CoreXY | — | — | [BOM](https://docs.google.com/spreadsheets/d/1k5knQOW3YX01BzTAEe6YCPVp2iNppOEKYJrqB6Ln_Wk/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/ccf745a3232adcedee163729/w/32082f8119c17ae81d2ba337/e/7da9f0f6822236e671d3e7e1) |
| 📷 | <a id="simplecore"></a>[**SimpleCore**](https://www.printables.com/model/1473500-simplecore) · *Rolohaun* — budget-friendly CoreXY with triple-Z bed and an expandable frame. | CoreXY | ~215×220×220 | — | [Files](https://www.printables.com/model/1473500-simplecore/files) · [STEP (older MK1)](https://github.com/rolohaun/SimpleCore/blob/HEAD/CAD/SimpleCore%20MK1.step) |
| 📷 | <a id="panda-mini"></a>[**Panda Mini**](https://www.printables.com/model/571947-panda-mini-corexy-3d-printer) · *Rolohaun* — small-format CoreXY. | CoreXY | 140×140×? | — | [Files](https://www.printables.com/model/571947-panda-mini-corexy-3d-printer/files) |
| 📷 | <a id="encore"></a>[**Encore**](https://github.com/alexyu132/encore) · *Alex Yu* — 120 mm printed-frame CoreXY with a filament-box-sized footprint. | CoreXY | 120×120×120 | 219×221×262 (body) | [STEP](https://github.com/alexyu132/encore/blob/main/encore.step) · [BOM](https://github.com/alexyu132/encore/blob/main/documentation/BOM.md) · [Build guide (WIP)](https://github.com/alexyu132/encore/blob/main/documentation/build%20guide/build%20guide.md) · [Video](https://www.youtube.com/watch?v=9xukniyO6fI) |
| 📷 | <a id="babycube"></a>[**BabyCube**](https://github.com/martinbudden/BabyCube) · *Martin Budden* — printed-frame mini CoreXY with linear rails and a roughly 90 × 80 × 60 mm build volume. | CoreXY | ~90×80×60 | ~248×272×211 (enclosing) | [Build guide and BOM](https://github.com/martinbudden/BabyCube/blob/main/BC200/readme.md) · [OpenSCAD source](https://github.com/martinbudden/BabyCube/tree/main/scad) · [Build videos](https://www.youtube.com/watch?list=PLbNI1Rcik-oIJZLZGHtmtgYNiHBKnzX2O&v=Hourt_4GOHs) |
| 📷 | <a id="maybecube"></a>[**MaybeCube**](https://github.com/martinbudden/MaybeCube) · *Martin Budden* — BabyCube's larger, configurable extrusion-frame sibling. | CoreXY | MC300: 185×185×200<br>MC350: 225×225×235<br>MC400: 275×275×285 | MC300: 340×340×420<br>MC350: 390×390×470<br>MC400: 440×440×520 | [MC300RB guide/BOM](https://github.com/martinbudden/MaybeCube/blob/main/MC300RB/readme.md) · [MC350 guide/BOM](https://github.com/martinbudden/MaybeCube/blob/main/MC350/readme.md) · [OpenSCAD source](https://github.com/martinbudden/MaybeCube/tree/main/scad) |
| 📷 | <a id="little-cube"></a>[**Little Cube**](https://www.thingiverse.com/thing:4487878) · *longlh / looong-made* — CoreXY with a 100 × 100 × 100 mm print volume, fixed bed, and belt-driven Z; an involved self-sourced build. | CoreXY | 100×100×100 | — | [Files and assembly notes](https://www.thingiverse.com/thing:4487878/files) · [Creator build story](https://looong-made.com/little-cube-lockdown-corexy-build/) |
| 📷 | <a id="minicube-kotvic"></a>[**MiniCube (Kotvic)**](https://www.thingiverse.com/thing:4795475) — compact CoreXY with Fusion 360 files; marked work in progress and missing assembly instructions. | CoreXY / experimental | 149×140×135 | 265×265×265 (body) | [Design files](https://www.thingiverse.com/thing:4795475/files) |
| 📷 | <a id="mini-cube-ichalix"></a>[**3d Mini Cube (iChalix)**](https://www.thingiverse.com/thing:3910543) — 120 mm BLV MGN Cube derivative with a single Z axis; documentation remains work in progress. | CoreXY / BLV derivative | 120×120×110 | ~325×355×338 (frame) | [STEP and printable files](https://www.thingiverse.com/thing:3910543/files) |
| 📷 | <a id="bastion"></a>[**Bastion**](https://www.printables.com/model/748800-bastion-3d-printer) · *Rolohaun* — triple independent Z and a Prusa Mini bed. | CoreXY | 180×180×? | — | [BOM](https://docs.google.com/spreadsheets/d/1l0jujA7NeqoZIqLFWoQa9GS_q04f8Wfkya9Il5d2ubA/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/256743a99b7cb9b4ae8f45f9/w/29df722021bf3c0e59d7c8ae/e/ff9493cea103644b334a3c7a) |
| 📷 | <a id="fenrir"></a>[**Fenrir**](https://www.makerviking.com/wiki/fenrir-corexy-3d-printer) · *MakerViking* — mostly printed CoreXY prototype; confirm file release before planning a build. | CoreXY / prototype | — | — | [Creator video](https://www.youtube.com/watch?v=qJi_0GzD9xU) |
| 📷 | <a id="3di-cnc-corexy"></a>[**3DI-CNC CoreXY**](https://www.youtube.com/watch?v=Kd5KnM2bmIE) · *3DI-CNC* — custom prototype with a liquid-cooled printhead; a public build package has not been confirmed. | CoreXY / prototype | — | — | [Printhead update](https://www.youtube.com/watch?v=JoVNW_hJGEU) · [2025 test](https://www.youtube.com/watch?v=M1lzhpFA2mY) |
| 📷 | <a id="the100"></a>[**THE100**](https://github.com/mszturc/THE100) · *Matt the Printing Nerd* — fast design with a printed frame. | CoreXY | ~165×165×165† | — | [STEP](https://github.com/mszturc/THE100/blob/HEAD/STEP/The%20100%20v1.1.step) · [Docs](https://github.com/mszturc/THE100/tree/HEAD/Docs) |
| 📷 | <a id="t250"></a>[**T250**](https://github.com/mszturc/T250) · *Matt the Printing Nerd* — larger high-speed successor to THE100. | CoreXY | 192×212×175 | — | [STEP](https://github.com/mszturc/T250/blob/HEAD/CAD/T250-v1.0-final.step) · [Docs](https://github.com/mszturc/T250/tree/HEAD/Docs) |
| 📷 | <a id="fusebox3"></a>[**FuseBox3**](https://github.com/alexyu132/fusebox3) · *Alex Yu* — midsize CoreXY using linear rails and a belt-driven Z; creator marks it under development. | CoreXY / experimental | 235×235×235 | 350×372×427 (frame) | [BOM](https://github.com/alexyu132/fusebox3/blob/master/documentation/BOM.md) · [Design file](https://github.com/alexyu132/fusebox3/blob/master/fusebox3.skp) |
| 📷 | <a id="fusebox2"></a>[**FuseBox2 / 2R**](https://github.com/alexyu132/fusebox2) · *Alex Yu* — earlier compact CoreXY; the creator recommends the 2R rail-gantry variant for a fresh build. | CoreXY / variants | 2: 210×200×210<br>2R: 210×205×210 | 390×340×412 | [2R CAD](https://github.com/alexyu132/fusebox2/blob/master/FuseBox2R.skp) · [Build tips](https://github.com/alexyu132/fusebox2/blob/master/Build%20Tips.md) · [BOM](https://github.com/alexyu132/fusebox2#bom) |
| 📷 | <a id="denali"></a>[**Denali**](https://github.com/Annex-Engineering/Denali) · *Annex Engineering* — scalable enclosed CoreXY with a three-motor moving bed; repository is archived. | CoreXY | 200: 200×200×200†<br>250: 250×250×200†<br>350: 350×350×300† | 200: ~380×380×620†<br>250: ~430×430×620†<br>350: ~530×530×720† | [CAD](https://github.com/Annex-Engineering/Denali/tree/master/CAD) · [STLs](https://github.com/Annex-Engineering/Denali/tree/master/STLs) · [BOM](https://docs.google.com/spreadsheets/d/1O3eyVuQ6M4F03MJSDs4Z71_XyNjXL5HFTZr1jsaAtRc/edit) |
| 📷 | <a id="snakeoil-xy"></a>[**SnakeOil XY**](https://github.com/SnakeOilXY/SnakeOil-XY) · *SnakeOilXY* — configurable CoreXY with standard, IDEX, and four-motor variants. | CoreXY / variants | 180: 180×180×180†<br>250: 250×240×230† | 180: ~400×390×520†<br>250: ~490×450×570† | [CAD](https://github.com/SnakeOilXY/SnakeOil-XY/tree/master/CAD) · [Manual](https://github.com/SnakeOilXY/SnakeOil-XY/tree/master/Doc) |
| 📷 | <a id="clock-3"></a>[**Clock 3**](https://github.com/jon-harper/clock-3) · *Jon Harper* — enclosed, temperature-controlled prototype; development is halted and the full Fusion assembly was not released. | CoreXY / experimental | 300×300×350 | ~640×675×875† | [BOM](https://github.com/jon-harper/clock-3/tree/main/BOM) · [STLs](https://github.com/jon-harper/clock-3/tree/main/STL) · [Docs](https://github.com/jon-harper/clock-3/tree/main/docs) |
| 📷 | <a id="micron"></a>[**Micron**](https://github.com/PrintersForAnts/Micron) · *Printers for Ants* — miniature Voron-inspired enclosed build. | CoreXY | 120: 120×120×?<br>180: 180×180×? | — | [CAD](https://github.com/PrintersForAnts/Micron/tree/HEAD/CAD) · [Manual](https://github.com/PrintersForAnts/Micron/blob/HEAD/Documentation/Micron_R1_Manual_WIP.pdf) |
| 📷 | <a id="salad-fork"></a>[**Salad Fork**](https://github.com/PrintersForAnts/Salad_Fork) · *Printers for Ants* — small Trident-inspired build. | CoreXY | 120: 120×120×?<br>160: 160×160×?<br>180: 180×180×? | — | [CAD](https://github.com/PrintersForAnts/Salad_Fork/tree/HEAD/CAD) · [Manual](https://github.com/PrintersForAnts/Salad_Fork/blob/HEAD/Salad%20Fork%20Manual.pdf) |
| 📷 | <a id="tiny-t"></a>[**Tiny-T**](https://github.com/PrintersForAnts/Tiny-T) · *Printers for Ants* — revision 2.0 scales the Voron Trident layout down to a 150 mm cube. | CoreXY | 150×150×150 | — | [CAD](https://github.com/PrintersForAnts/Tiny-T/tree/main/CAD) · [STLs](https://github.com/PrintersForAnts/Tiny-T/tree/main/STLs) · [Components](https://github.com/PrintersForAnts/Tiny-T#components) |
| 📷 | <a id="jubilee"></a>[**Jubilee**](https://github.com/machineagency/jubilee) · *Machine Agency* — open tool-changing platform. | CoreXY / toolchanger | 300×300×300† | 476×604×558† | [STEP](https://github.com/machineagency/jubilee/blob/HEAD/frame/cads/STEP/jubilee.STEP) |
| 📷 | <a id="valkyrie"></a>[**Project Valkyrie**](https://github.com/3D-Experiments/Project-Valkyrie) · *3D Experiments* — inverted CoreXY for experimental builds. | Inverted CoreXY | — | — | [Design library](https://github.com/3D-Experiments/Project-Valkyrie/tree/HEAD/Document%20Library) |

### Cartesian / CoreXZ

Includes independently driven X/Y layouts; the specific motion system is stated in each row.

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="prusa-i3"></a>[**Original Prusa i3**](https://github.com/prusa3d/Original-Prusa-i3) · *Prusa family* — an influential open-design moving-bed platform. | Cartesian | — | — | [Parts and source](https://github.com/prusa3d/Original-Prusa-i3) |
| 📷 | <a id="ender-3"></a>[**Original Ender-3**](https://github.com/Creality3DPrinting/Ender-3) · *Creality* — the original open-source Ender-3 hardware release, including mechanical and electronics files. | Cartesian | 220×220×250 | ~440×410×465 | [Mechanical CAD](https://github.com/Creality3DPrinting/Ender-3/tree/master/Ender-3%20Mechanical) · [Firmware](https://github.com/Creality3DPrinting/Ender-3/tree/master/Ender-3%20Firmware%20%28Marlin%29) · [Size source](https://devstore.creality.com/blogs/all/ender-3-bed-size) |
| 📷 | <a id="rook-mk2"></a>[**Rook MK2**](https://www.printables.com/model/1644597-rook-mk2) · *Rolohaun / Rook family* — fully printed frame; creator labels this a beta release. | Cartesian | 120×120×? | — | [BOM](https://docs.google.com/spreadsheets/d/18EqrtU4kwdb6v4gPMTdCcCdBVbxlF5-EhFE0hZtxHoA/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/5010167e95003ed32232fd0e/w/756fbf38edf59fb734f7365c/e/e647ceb1e4681ba492e8722b) |
| 📷 | <a id="kappy"></a>[**Kappy**](https://www.printables.com/model/625544-kappy-3d-printer) · *Rolohaun* — small, beginner-oriented DIY printer. | Cartesian | 120×120×100 | — | [Manual](https://drive.google.com/file/d/1iMX36I9zHaRenk27AsYJOz9wUkhZm12h/view) · [BOM](https://docs.google.com/spreadsheets/d/10yJ0s7zZR3LtqlApnVSDP2MTe3I9gViXxYyVxZ6Vb1I/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/e3d1e390ee25e4cecb91b755/w/71cf613e30e4a447f8845523/e/ca80937f1c3e35dd2362d739) |
| 📷 | <a id="ratrig-v-minion"></a>[**Rat Rig V-Minion**](https://github.com/Rat-Rig/V-Minion) · *Rat Rig family* — compact 180 mm cantilevered Cartesian with linear rails. | Cartesian | 180×180×180 | — | [Printed parts and panels](https://github.com/Rat-Rig/V-Minion/tree/main/cad) · [Build guide](https://rat-rig.github.io/V-Minion/) |
| 📷 | <a id="tictac-2-1"></a>[**TicTac 2.1**](https://www.printables.com/model/416884-tictac-21) · *Squirrelbrain* — a miniaturized V-Minion-derived Cartesian printer. | Cartesian / V-Minion derivative | 120×120×120 | — | [Files](https://www.printables.com/model/416884-tictac-21/files) |
| 📷 | <a id="annex-k3"></a>[**Annex K3 / Gasherbrum**](https://github.com/Annex-Engineering/Gasherbrum-K3) · *Annex Engineering* — small enclosed machine with separate X and Y drives. | CartesianXY | ~180×180×180 | — | [Release files](https://github.com/Annex-Engineering/Gasherbrum-K3/tree/HEAD/Release_1_2) |
| 📷 | <a id="voron-switchwire"></a>[**Voron Switchwire**](https://github.com/VoronDesign/Voron-Switchwire) · *Voron family* — belt-driven CoreXZ layout. | CoreXZ | — | — | [CAD](https://github.com/VoronDesign/Voron-Switchwire/tree/HEAD/CAD) · [Manual](https://github.com/VoronDesign/Voron-Switchwire/blob/HEAD/Manuals/Assembly_Manual_SW.pdf) |
| 📷 | <a id="lh-stinger"></a>[**LH Stinger**](https://github.com/lhndo/LH-Stinger) · *LHndo* — performance-focused moving-bed design. | Cartesian | 235×235×200 | — | [CAD](https://github.com/lhndo/LH-Stinger/tree/HEAD/CAD) · [Wiki](https://github.com/lhndo/LH-Stinger/wiki) |

### Delta

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="delta-flyer"></a>[**Delta Flyer**](https://www.printables.com/model/1327596-delta-flyer-3d-printer) · *Rolohaun / Kanrog* — compact delta with linear rails and a published manual. | Delta | Ø115×115 | — | [Manual](https://kanrog.github.io/Delta-Flyer/) · [BOM](https://docs.google.com/spreadsheets/d/1400rbdxxYbIA15yIi4UiYHQk1Ul_DCyP7nSTH7CUpFE/edit) · [Onshape CAD (sign-in)](https://cad.onshape.com/documents/de9bc61850e74a1717307838/w/2a32f2b0d6edf7beeb9fcbf7/e/392043168b1092bab001d0df) |
| 📷 | <a id="min-micro-delta"></a>[**MIN Micro Delta**](https://www.printables.com/model/857334-min-micro-delta-3d-printer) · *Rolohaun* — a very small delta project. | Delta | Ø70×95 | — | [Files](https://www.printables.com/model/857334-min-micro-delta-3d-printer/files) |
| 📷 | <a id="phoenix-delta"></a>[**PhoenixDelta**](https://github.com/rolohaun/PhoenixDelta) · *Rolohaun* — large experimental delta built around a 350 mm bed; work in progress. | Delta / experimental | — | — | [STEP](https://github.com/rolohaun/PhoenixDelta/blob/main/Phoenix%20v136.step) · [Parts list](https://github.com/rolohaun/PhoenixDelta#phoenix-delta) |

### Other motion systems

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="defiant"></a>[**Defiant**](https://github.com/rolohaun/Defiant) · *Rolohaun* — beta CroXY build with three independently driven Z motors; currently unenclosable. | CroXY / experimental | 250×250×250 | — | [CAD](https://github.com/rolohaun/Defiant/tree/main/CAD) · [BOM (WIP)](https://docs.google.com/spreadsheets/d/1MMBtSAIVklJtp9cDsU00cnw-aWT4j8f6p9V2ZHv14fQ/edit) |
| 📷 | <a id="hangprinter"></a>[**Hangprinter**](https://github.com/tobbelobb/hangprinter) · *Torbjørn Ludvigsen* — cable-suspended, frameless printer. | Cable-driven | — | — | [Project files](https://github.com/tobbelobb/hangprinter) |
| 📷 | <a id="white-knight-belt"></a>[**White Knight Belt**](https://www.thingiverse.com/thing:3977443) — DIY continuous-print belt concept. | Belt printer | — | — | [Files](https://www.thingiverse.com/thing:3977443/files) |
| 📷 | <a id="babybelt-pro"></a>[**BabyBelt Pro**](https://github.com/RobMink/BabyBeltPro) · *Rob Mink* — compact belt printer. | Belt printer | — | — | [STEP](https://github.com/RobMink/BabyBeltPro/blob/HEAD/CAD/BBProV2POINT6.stp) · [Build guide](https://github.com/RobMink/BabyBeltPro/blob/HEAD/documentation/bbpv2_build_guide.md) |
| 📷 | <a id="infini-z"></a>[**Infini-Z**](https://projectquine.substack.com/p/the-first-infini-z) · *SunShine / Andras* — experimental self-climbing Z axis. | Climbing Z | — | — | [Model files](https://cults3d.com/en/3d-model/tool/infini-z-3d-printer) |
| 📷 | <a id="positron-v3"></a>[**Positron V3.2**](https://github.com/Positron3D/Positron) · *Positron Team / Kralyn* — compact inverted printer that folds for transport. | Inverted / folding | 180×180×165 | 200×200×270 (open)<br>200×200×80 (folded) | [CAD and parts](https://github.com/Positron3D/Positron/tree/main/Printed%20Parts%20%26%20CAD%20Models) · [Size source](https://store.ldomotion.com/products/positron-s1-diy-3d-printer-kit) · [Original V3](https://github.com/KRALYN/PositronV3) |
| 📷 | <a id="lemontron"></a>[**Lemontron**](https://lemontron.com/lemontron-rev-e/) · *Lemontron* — portable inverted design; Rev E files are released, with the earlier guide used for assembly. | Inverted / portable | 180×180×165 | — | [Rev E files](https://lemontron.com/lemontron-rev-e/printed-parts/) · [Rev A build guide](https://lemontron.com/lemontron-rev-a/build-guide/) · [BOM](https://lemontron.com/lemontron-rev-e/bom/) · [Creator video](https://www.youtube.com/watch?v=n6l3GvkE4QU) |

## Conversions

These reuse a donor printer or modify an existing printer family. Check the exact donor model and revision before ordering parts.

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="duender"></a>[**Duender**](https://github.com/Irbis3D/Duender) · *Irbis3D* — turns parts from two Ender-3 printers into one CoreXY. | Ender-3 → CoreXY | — | — | [STEP kits](https://github.com/Irbis3D/Duender/tree/HEAD/STEP%20KITS) · [Manual](https://github.com/Irbis3D/Duender/tree/HEAD/Manual) |
| 📷 | <a id="ender-3-ng"></a>[**Ender-3 NG**](https://www.printables.com/model/922401-ender-3-ng-v12-corexy-conversion) · *RH3D* — Ender-3 CoreXY conversion with a dedicated guide. | Ender-3 → CoreXY | — | — | [Files](https://rh3d.xyz/E3NG_v1_2/standard/files) · [Build guide](https://rh3d.xyz/E3NG_v1_2/standard/build_guide) |
| 📷 | <a id="proosaxy"></a>[**ProosaXY**](https://github.com/SnakeOilXY/ProosaXY) · *SnakeOilXY* — Prusa MK3/S CoreXY conversion that reuses donor parts; requires irreversible drilling and cutting. | Prusa MK3/S → CoreXY | — | — | [Source CAD](https://github.com/SnakeOilXY/ProosaXY/tree/master/src) · [STLs](https://github.com/SnakeOilXY/ProosaXY/tree/master/STLs) · [BOM](https://github.com/SnakeOilXY/ProosaXY#bom) |
| 📷 | <a id="mercury-one"></a>[**Mercury One**](https://github.com/ZeroGDesign/MercuryOne) · *ZeroG* — CoreXY conversion for Ender-5 family machines. | Ender-5 → CoreXY | — | — | [CAD](https://github.com/ZeroGDesign/MercuryOne/tree/HEAD/CAD) · [Mercury One.1 build guide](https://docs.zerog.one/manual/build/mercury_eva) |
| 📷 | <a id="double-dragon"></a>[**Double Dragon**](https://github.com/zruncho3d/double-dragon) · *zruncho3d* — Voron V0-derived dual-extrusion experiment. | V0-derived IDEX mod | — | — | [CAD](https://github.com/zruncho3d/double-dragon/tree/HEAD/CAD) |
| 📷 | <a id="dueling-zero"></a>[**Dueling Zero**](https://github.com/zruncho3d/DuelingZero) · *zruncho3d* — Voron V0-derived dual-gantry project. | V0-derived dual-gantry mod | — | — | [CAD](https://github.com/zruncho3d/DuelingZero/tree/HEAD/CAD) · [Instructions](https://github.com/zruncho3d/DuelingZero/blob/HEAD/INSTRUCTIONS.md) |
| 📷 | <a id="f-zero"></a>[**F-Zero**](https://github.com/zruncho3d/f-zero) · *zruncho3d* — V0-component flying-gantry design that can be built fresh or as an upgrade. | V0-derived CoreXY | ~120×120×120 | — | [CAD](https://github.com/zruncho3d/f-zero/tree/main/CAD) · [Build notes](https://github.com/zruncho3d/f-zero#buildlog-and-design-doc) |
| 📷 | <a id="tri-zero"></a>[**Tri-Zero**](https://github.com/zruncho3d/tri-zero) · *zruncho3d* — adds triple belted Z and automatic bed leveling to a Voron V0; also supports a fresh build. | V0-derived CoreXY mod | standard: 120×120×?<br>Plus50: 170×170×? | — | [CAD](https://github.com/zruncho3d/tri-zero/tree/main/CAD) · [Instructions](https://github.com/zruncho3d/tri-zero/blob/main/INSTRUCTIONS.md) · [Plus50 notes](https://github.com/zruncho3d/tri-zero/blob/main/PLUS50.md) |

## Historical designs

Foundational and older community designs remain useful for learning and restoration. A wiki page here may document the design without offering a current, complete build package.

| Photo | Printer and why it’s interesting | Build type | Build volume (X×Y×Z) | Exterior (W×D×H) | Resources |
| --- | --- | --- | --- | --- | --- |
| 📷 | <a id="darwin"></a>[**Darwin**](https://reprap.org/wiki/Darwin) · *RepRap* — one of the earliest self-replicating printer designs. | Cartesian | — | — | — |
| 📷 | <a id="mendel"></a>[**Mendel**](https://reprap.org/wiki/Mendel) · *RepRap* — influential second-generation RepRap. | Cartesian | — | — | — |
| 📷 | <a id="prusa-mendel-i2"></a>[**Prusa Mendel i2**](https://reprap.org/wiki/Prusa_Mendel) · *Prusa / RepRap* — an early simplification of Mendel. | Cartesian | — | — | — |
| 📷 | <a id="prusa-i3-early"></a>[**Prusa i3 (early)**](https://reprap.org/wiki/Prusa_i3) · *Prusa / RepRap* — early i3 documentation for the design lineage. | Cartesian | — | — | — |
| 📷 | <a id="huxley"></a>[**Huxley**](https://reprap.org/wiki/Huxley) · *RepRap* — compact early RepRap. | Cartesian | — | — | — |
| 📷 | <a id="wallace"></a>[**Wallace**](https://reprap.org/wiki/Wallace) · *RepRap* — minimalist early design. | Cartesian | — | — | — |
| 📷 | <a id="tantillus"></a>[**Tantillus**](https://reprap.org/wiki/Tantillus) · *RepRap* — small enclosed printer with printed structural parts. | Cartesian | — | — | — |
| 📷 | <a id="ultimaker-original"></a>[**Ultimaker Original**](https://github.com/Ultimaker/UltimakerOriginal) · *Ultimaker* — open-design wooden-frame machine. | Cartesian | — | — | [BOM](https://github.com/Ultimaker/UltimakerOriginal/tree/HEAD/BOM) |
| 📷 | <a id="mendelmax"></a>[**MendelMax**](https://github.com/maxbots/MendelMax) · *Maxbots* — aluminum-extrusion Mendel variant. | Cartesian | — | — | [STEP](https://github.com/maxbots/MendelMax/blob/HEAD/MendelMax.stp) · [Wiki](https://reprap.org/wiki/MendelMax) |
| 📷 | <a id="mendel90"></a>[**Mendel90**](https://github.com/nophead/Mendel90) · *nophead* — sheet-frame Mendel variant. | Cartesian | — | — | [Project files](https://github.com/nophead/Mendel90) |
| 📷 | <a id="smartrap"></a>[**Smartrap**](https://reprap.org/wiki/Smartrap_mini) — compact, low-part-count RepRap design. | Cartesian | — | — | — |
| 📷 | <a id="snappy"></a>[**Snappy**](https://github.com/revarbat/snappy-reprap) · *revarbat* — mostly printed, snap-together RepRap. | Cartesian | — | — | [Docs](https://github.com/revarbat/snappy-reprap/tree/HEAD/docs) |
| 📷 | <a id="tiny-m"></a>[**Tiny-M**](https://github.com/gsl12/Tiny-M) · *gsl12* — archived 150 mm Voron V0-inspired CoreXY; creator lists V4 as current and V5 as beta. | CoreXY | 150×150×150 | — | [V4 Onshape CAD](https://cad.onshape.com/documents/f842588d372acab22a4ce687/w/3332acdd7c7bf7fc53ddefb6/e/ce1bfb58b96a9bb3b38b0502) · [Older V3 CAD](https://github.com/gsl12/Tiny-M/tree/master/CAD) · [BOM](https://github.com/gsl12/Tiny-M/tree/master/BOM) |
| 📷 | <a id="voron-legacy"></a>[**Voron Legacy**](https://github.com/VoronDesign/Voron-Legacy) · *Voron family* — a released throwback design honoring Voron 1.0. | CoreXY | — | — | [CAD](https://github.com/VoronDesign/Voron-Legacy/tree/main/CAD) · [STLs](https://github.com/VoronDesign/Voron-Legacy/tree/main/STLs) · [Configurator/BOM](https://vorondesign.com/voron_legacy) |
| 📷 | <a id="foldarap"></a>[**FoldaRap**](https://github.com/EmmanuelG/Foldarap) · *Emmanuel Gilli* — folding portable RepRap. | Cartesian / folding | — | — | [Source files](https://github.com/EmmanuelG/Foldarap) |
| 📷 | <a id="itopie"></a>[**ITopie**](https://reprap.org/wiki/ITopie) — older framed RepRap design. | Cartesian | — | — | — |
| 📷 | <a id="rostock"></a>[**Rostock**](https://reprap.org/wiki/Rostock) · *RepRap* — foundational parallel-arm delta. | Delta | — | — | — |
| 📷 | <a id="kossel"></a>[**Kossel**](https://reprap.org/wiki/Kossel) · *RepRap* — a widely replicated delta lineage. | Delta | — | — | — |
| 📷 | <a id="cerberus"></a>[**Cerberus**](https://reprap.org/wiki/Cerberus) · *RepRap* — older delta variant. | Delta | — | — | — |
| 📷 | <a id="lisa-simpson"></a>[**LISA Simpson**](https://reprap.org/wiki/LISA_Simpson) · *Simpson family* — experimental grounded delta variant. | Grounded delta | — | — | — |
| 📷 | <a id="gus-simpson"></a>[**GUS Simpson**](https://reprap.org/wiki/GUS_Simpson) · *Simpson family* — experimental grounded delta prototype. | Grounded delta | — | — | — |
| 📷 | <a id="tevo-little-monster"></a>[**Tevo Little Monster**](https://github.com/Homers3D/Tevo-Little-Monster) · *community reference* — large commercial delta with owner-maintained firmware and documents. | Delta | — | — | [Firmware and docs](https://github.com/Homers3D/Tevo-Little-Monster) |
| 📷 | <a id="cherry-pi-delta"></a>[**Cherry Pi Delta**](https://www.thingiverse.com/thing:210028) — older community delta design. | Delta | — | — | [Files](https://www.thingiverse.com/thing:210028/files) |
| 📷 | <a id="reprap-morgan"></a>[**RepRap Morgan**](https://reprap.org/wiki/RepRap_Morgan) · *RepRap* — articulated-arm alternative to Cartesian gantries. | SCARA | — | — | — |
| 📷 | <a id="wally"></a>[**Wally**](https://reprap.org/wiki/Wally) · *RepRap* — compact arm-based experiment. | SCARA | — | — | — |
| 📷 | <a id="r360-polar"></a>[**R-360 Polar**](https://reprap.org/wiki/R_360) · *RepRap* — radial/polar motion experiment. | Polar | — | — | — |
| 📷 | <a id="tripteron"></a>[**Tripteron**](https://reprap.org/wiki/Tripteron) · *RepRap* — three orthogonal parallel arms. | Parallel kinematics | — | — | — |

## Browse mini and portable printers

Small printers span several motion systems, so this is a shortcut to their catalog rows. “Mini” here means designed around a small build volume, a compact footprint, or portability; it is not a fixed size rating.

- **Compact CoreXY:** [BabyCube](#babycube) · [Encore](#encore) · [Little Cube](#little-cube) · [Voron V0](#voron-v0) · [Rook MK1](#rook-mk1) · [Panda Mini](#panda-mini) · [Micron](#micron) · [Salad Fork](#salad-fork) · [Tiny-T](#tiny-t) · [Tiny-M](#tiny-m) · [MiniCube (Kotvic)](#minicube-kotvic) · [3d Mini Cube (iChalix)](#mini-cube-ichalix) · [F-Zero](#f-zero) · [Tri-Zero](#tri-zero)
- **Small Cartesian:** [TicTac 2.1](#tictac-2-1) · [Rat Rig V-Minion](#ratrig-v-minion) · [Kappy](#kappy) · [Rook MK2](#rook-mk2)
- **Portable inverted:** [Positron V3.2](#positron-v3) · [Lemontron](#lemontron)
- **Small delta or belt:** [MIN Micro Delta](#min-micro-delta) · [Delta Flyer](#delta-flyer) · [BabyBelt Pro](#babybelt-pro)

### Mini footprint comparison

For a desk, **extra width and depth beyond printable XY** is easier to picture than an area ratio. Each value is exterior W minus printable X, and exterior D minus printable Y; it is not a required clearance on each side. The measurements use different body, enclosing, or open configurations, so check spool placement and bed travel before planning a tight space.

| Printer | Printable XY | Reported footprint | Extra W × D |
| --- | --- | --- | --- |
| [Positron V3.2](#positron-v3) (open) | 180×180 | 200×200 | +20×20 mm |
| [Encore](#encore) (body) | 120×120 | 219×221 | +99×101 mm |
| [Voron V0](#voron-v0) † | 120×120 | 230×230† | +110×110 mm† |
| [MiniCube (Kotvic)](#minicube-kotvic) (body) | 149×140 | 265×265 | +116×125 mm |
| [BabyCube](#babycube) (enclosing) | ~90×80 | ~248×272 | ~+158×192 mm |

Kotvic's MiniCube grows to **265×340×350 mm** with the spool, extruder, and Bowden tube included. BabyCube's enclosing figure excludes its spool, Bowden tube, and wiring. Those accessory differences matter more than a small difference in the table's overhead.

## Browse by maker or family

The same printer appears only once above. These links jump to its row; use your browser's page search for smaller maker tags.

- **[Rolohaun / Rook](https://www.printables.com/@Rolohaun/models):** [Rook MK1](#rook-mk1) · [Rook MK2](#rook-mk2) · [Rook 2020 MK1](#rook-2020-mk1) · [Rook 2020 MK2](#rook-2020-mk2) · [SimpleCore](#simplecore) · [Panda Mini](#panda-mini) · [Bastion](#bastion) · [Defiant](#defiant) · [Kappy](#kappy) · [MIN Micro Delta](#min-micro-delta) · [Delta Flyer](#delta-flyer) · [PhoenixDelta](#phoenix-delta)
- **Rat Rig:** [V-Core 4.1](#ratrig-v-core-4-1) · [V-Core 3](#ratrig-v-core-3) · [V-Minion](#ratrig-v-minion). [TicTac 2.1](#tictac-2-1) is a related miniaturized design.
- **BLV MGN Cube:** [BLV MGN Cube](#blv-mgn-cube) · [3d Mini Cube](#mini-cube-ichalix) derivative.
- **Voron:** [V0](#voron-v0) · [Trident](#voron-trident) · [2.4](#voron-2-4) · [Switchwire](#voron-switchwire) · [Legacy](#voron-legacy). [Double Dragon](#double-dragon), [Dueling Zero](#dueling-zero), [F-Zero](#f-zero), and [Tri-Zero](#tri-zero) are related V0-derived designs.
- **Printers for Ants:** [Micron](#micron) · [Salad Fork](#salad-fork) · [Tiny-T](#tiny-t)
- **gsl12:** [Tiny-M](#tiny-m)
- **Martin Budden:** [BabyCube](#babycube) · [MaybeCube](#maybecube)
- **Alex Yu:** [Encore](#encore) · [FuseBox3](#fusebox3) · [FuseBox2 / 2R](#fusebox2)
- **zruncho3d:** [F-Zero](#f-zero) · [Tri-Zero](#tri-zero) · [Double Dragon](#double-dragon) · [Dueling Zero](#dueling-zero)
- **SnakeOilXY:** [SnakeOil XY](#snakeoil-xy) · [ProosaXY](#proosaxy)
- **[3DI-CNC](https://www.youtube.com/@3dicnc):** [CoreXY prototype](#3di-cnc-corexy)
- **SecKit:** [SK-Go](#seckit-sk-go) · [SK-Tank](#seckit-sk-tank)
- **Prusa / RepRap:** [Original Prusa i3](#prusa-i3) · [early i3](#prusa-i3-early) · [Prusa Mendel i2](#prusa-mendel-i2)
- **Matt the Printing Nerd:** [THE100](#the100) · [T250](#t250)

### Suggest a printer or resource

A useful addition has a specific printer design and a project page, plus a short reason it is interesting. Direct links to a build guide, BOM, STEP/CAD, and creator video are welcome when available. For photos, include the source and reuse permission. Avoid broad homepages, dead links, duplicate listings, and unverified claims of “best” or “cheapest.”

The former list is preserved in [`bak-README.md`](bak-README.md). Its **Sethi H-Bot** link no longer resolves, and its **RepRap H-Bot Project** link describes a motion system rather than a specific printer; both remain in the backup pending a suitable project source. The old **Saturn Delta** link could not be tied to a specific delta printer, and **Sixi** is a robotic arm rather than a printer; those entries also remain in the backup.
