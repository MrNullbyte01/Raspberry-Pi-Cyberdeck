# Raspberry Pi Cyberdeck

A personal portable-computing project inspired by the Raspberry Pi cyberdeck community and, in particular, **Tommi Laukkanen's Cyberdore** build.

> **Status:** Reference-based project repository. It currently contains 10 STL enclosure/assembly files and a reference PDF. No personal assembly photos, hardware bill of materials, or functional test results have been published yet.

## Inspiration and attribution

The project takes inspiration from Tommi Laukkanen's *Cyberdore — Raspberry Pi powered Cyberdeck*. In his original write-up, Laukkanen explains that he initially used a **Raspberry Pi 3 Model B+**, then changed to a **Raspberry Pi Zero W** to reduce power consumption. The design also explores a compact display, a small wireless keyboard, battery power, and a layered 3D-printed enclosure.

This repository documents **my own project and any changes I make**. It is not the original Cyberdore project, and Tommi Laukkanen is not the author of my build.

### Original project references

- [Tommi Laukkanen — Cyberdore: Raspberry Pi powered Cyberdeck](https://www.codeof.me/cyberdore-raspberry-pi-powered-cyberdeck/)
- [Tommi Laukkanen — Cyberdore 2064](https://www.codeof.me/cyberdore-2064-rpi0-based-cyberdeck-to-handle-netrunning-tasks-on-the-couch/)
- [Hackster.io — Cyberdore 2064 overview](https://www.hackster.io/news/tommi-laukkane-s-cyberdore-2064-blends-retro-futurism-with-a-raspberry-pi-zero-1adf96a6bed1)
- [Cyberdore 2064 3D model on Printables](https://www.printables.com/model/945411-cyberdore-2064-cyberdeck)

## Reference research and build plan

See [Cyberdore reference analysis and build plan](docs/reference-and-build-plan.md) for attribution, original references, and a template for documenting my own hardware choices.

## Project goals

- Build or document a portable Raspberry Pi-based computer.
- Integrate a display and compact keyboard.
- Plan portable power and safe cable management.
- Document the operating-system setup and practical use.
- Record original modifications rather than presenting reference designs as my own.

## Files currently in this repository

The repository currently includes the following 3D-printable STL files:

| File | Description |
|---|---|
| [Back cover.stl](Back%20cover.stl) | Enclosure back cover |
| [Cyberdeck bottom shell.stl](Cyberdeck%20bottom%20shell.stl) | Lower enclosure shell |
| [Cyberdeck screen mask.stl](Cyberdeck%20screen%20mask.stl) | Screen bezel / mask |
| [Cyberdeck top outer shell.stl](Cyberdeck%20top%20outer%20shell.stl) | Upper outer shell |
| [Cyberdeck top shell.stl](Cyberdeck%20top%20shell.stl) | Upper shell component |
| [Display holder v2.stl](Display%20holder%20v2.stl) | Revised display holder |
| [Display holder.stl](Display%20holder.stl) | Display holder |
| [Handle.stl](Handle.stl) | Handle component |
| [Lens holder.stl](Lens%20holder.stl) | Lens holder |
| [Power label.stl](Power%20label.stl) | Power label component |

A reference PDF is also stored in the repository. These files are available as model assets; their presence does not prove that the enclosure has been printed or assembled.

## Build log

| Area | Status |
|---|---|
| Cyberdore reference research | Documented |
| STL model files | 10 files present |
| Exact Raspberry Pi model in my own build | To be documented |
| Display and keyboard actually selected | To be documented |
| Battery and power arrangement | To be documented |
| 3D printing / assembly completed | Not yet evidenced |
| Operating system and setup | To be documented |
| Original photos and functional tests | To be added |

## Suggested repository structure

```text
Raspberry-Pi-Cyberdeck/
├── README.md
├── docs/
│   ├── bill-of-materials.md
│   ├── assembly-notes.md
│   └── software-setup.md
├── hardware/
├── software/
├── images/
└── build-log/
```

## Attribution and licensing

The reference links above belong to their respective authors and publishers. The Cyberdore 2064 3D-print files are published under **CC BY-NC-SA 4.0** according to the linked coverage; that licence applies to those files, not automatically to every part of this repository. If any original model files are reused, retain the required attribution, follow the non-commercial and share-alike terms, and identify modifications. Do not upload someone else's files as original work.

---
*Personal hardware learning project by MrNullbyte01. Inspired by the work of Tommi Laukkanen; independently documented and modified.*

## Current asset status

The portfolio's `assets/` folder did not contain original Cyberdeck build photos, wiring diagrams, or a hardware bill of materials. This repository does contain 10 STL model files and a reference PDF, but no evidence currently confirms that the parts have been printed or assembled. Add original photos, selected hardware details, and functional tests as the build progresses.
